# Modu� 3: Podstawy Vue.js
# Modu� 3: Podstawy Vue.js

## Lekcja 1: Tworzenie komponent�w i reu�ywalno�� kodu

### Teoria:

- Komponenty w Vue.js: jak tworzy�, reu�ywa� i komponowa� komponenty.

  - Dokumentacja: [Vue.js Components](https://vuejs.org/v2/guide/components.html)

### Przyk�ad:

`ue

<template>

  <div>

    <ChildComponent />

  </div>

</template>



<script>

import ChildComponent from './ChildComponent.vue'

export default {

  components: {

    ChildComponent

  }

}

</script>



### Proste zadanie:

- Stw�rz prosty komponent rodzica i komponent dziecka.

### Zaawansowane zadanie:

- Stw�rz bardziej z�o�on� hierarchi� komponent�w z przekazywaniem danych mi�dzy nimi.
