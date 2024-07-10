# Modu� 2: Tworzenie Podstawowej Aplikacji Vue
# Modu� 2: Tworzenie Podstawowej Aplikacji Vue

## Lekcja 1: Stw�rz i skonfiguruj prosty komponent Vue. Wyja�nij struktur� komponentu i jego cz�ci.

### Teoria:

- Komponenty Vue: Podstawowe elementy budowy aplikacji Vue.js, sk�adaj�ce si� z szablonu (template), logiki (script) i styl�w (style).

  - Dokumentacja: [Vue.js Components](https://vuejs.org/v2/guide/components.html)

### Przyk�ad:

`ue

<template>

  <div>

    <h1>{{ message }}</h1>

  </div>

</template>



<script>

export default {

  data() {

    return {

      message: 'Hello, Vue!'

    }

  }

}

</script>



<style scoped>

  h1 {

    color: blue;

  }

</style>
n

### Proste zadanie:

- Stw�rz komponent Vue, kt�ry wy�wietla wiadomo��.

### Zaawansowane zadanie:

- Dodaj mo�liwo�� interakcji z komponentem, np. przycisk zmieniaj�cy wy�wietlan� wiadomo��.
