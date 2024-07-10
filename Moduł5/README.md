# Modu³ 5: Optymalizacja i wydajnoœæ
# Modu³ 5: Optymalizacja i wydajnoœæ

## Lekcja 1: Lazy Loading i Code Splitting

### Teoria:

- Lazy Loading: jak ³adowaæ komponenty na ¿¹danie, aby poprawiæ wydajnoœæ aplikacji.

  - Dokumentacja: [Vue.js Lazy Loading](https://router.vuejs.org/guide/advanced/lazy-loading.html)

### Przyk³ad:

`js

const Foo = () => import('./Foo.vue')

export default {

  components: {

    Foo

  }

}



### Proste zadanie:

- Stwórz komponent, który ³aduje inny komponent na ¿¹danie.

### Zaawansowane zadanie:

- Zaimplementuj lazy loading dla wielu komponentów w swojej aplikacji.
