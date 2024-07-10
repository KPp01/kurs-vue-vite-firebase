# Modu� 5: Optymalizacja i wydajno��
# Modu� 5: Optymalizacja i wydajno��

## Lekcja 1: Lazy Loading i Code Splitting

### Teoria:

- Lazy Loading: jak �adowa� komponenty na ��danie, aby poprawi� wydajno�� aplikacji.

  - Dokumentacja: [Vue.js Lazy Loading](https://router.vuejs.org/guide/advanced/lazy-loading.html)

### Przyk�ad:

`js

const Foo = () => import('./Foo.vue')

export default {

  components: {

    Foo

  }

}



### Proste zadanie:

- Stw�rz komponent, kt�ry �aduje inny komponent na ��danie.

### Zaawansowane zadanie:

- Zaimplementuj lazy loading dla wielu komponent�w w swojej aplikacji.
