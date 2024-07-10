# Modu³ 2: Tworzenie Podstawowej Aplikacji Vue
# Modu³ 2: Tworzenie Podstawowej Aplikacji Vue

## Lekcja 1: Stwórz i skonfiguruj prosty komponent Vue. Wyjaœnij strukturê komponentu i jego czêœci.

### Teoria:

- Komponenty Vue: Podstawowe elementy budowy aplikacji Vue.js, sk³adaj¹ce siê z szablonu (template), logiki (script) i stylów (style).

  - Dokumentacja: [Vue.js Components](https://vuejs.org/v2/guide/components.html)

### Przyk³ad:

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

- Stwórz komponent Vue, który wyœwietla wiadomoœæ.

### Zaawansowane zadanie:

- Dodaj mo¿liwoœæ interakcji z komponentem, np. przycisk zmieniaj¹cy wyœwietlan¹ wiadomoœæ.
