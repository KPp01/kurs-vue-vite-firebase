# Modu³ 4: Zaawansowane koncepcje Vue.js
# Modu³ 4: Zaawansowane koncepcje Vue.js

## Lekcja 1: Render Functions i JSX

### Teoria:

- Render Functions: jak u¿ywaæ funkcji renderuj¹cych do tworzenia dynamicznych komponentów.

  - Dokumentacja: [Vue.js Render Functions](https://vuejs.org/v2/guide/render-function.html)

### Przyk³ad:

`ue

<script>

export default {

  render(h) {

    return h('div', { class: 'hello' }, 'Hello World')

  }

}

</script>



### Proste zadanie:

- Stwórz komponent wykorzystuj¹cy funkcjê renderuj¹c¹.

### Zaawansowane zadanie:

- U¿yj JSX do stworzenia dynamicznego komponentu z warunkowym renderowaniem.
