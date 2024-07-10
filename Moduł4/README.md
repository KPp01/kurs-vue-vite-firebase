# Modu� 4: Zaawansowane koncepcje Vue.js
# Modu� 4: Zaawansowane koncepcje Vue.js

## Lekcja 1: Render Functions i JSX

### Teoria:

- Render Functions: jak u�ywa� funkcji renderuj�cych do tworzenia dynamicznych komponent�w.

  - Dokumentacja: [Vue.js Render Functions](https://vuejs.org/v2/guide/render-function.html)

### Przyk�ad:

`ue

<script>

export default {

  render(h) {

    return h('div', { class: 'hello' }, 'Hello World')

  }

}

</script>



### Proste zadanie:

- Stw�rz komponent wykorzystuj�cy funkcj� renderuj�c�.

### Zaawansowane zadanie:

- U�yj JSX do stworzenia dynamicznego komponentu z warunkowym renderowaniem.
