# Modu³ 3: Podstawy Vue.js
# Modu³ 3: Podstawy Vue.js

## Lekcja 1: Tworzenie komponentów i reu¿ywalnoœæ kodu

### Teoria:

- Komponenty w Vue.js: jak tworzyæ, reu¿ywaæ i komponowaæ komponenty.

  - Dokumentacja: [Vue.js Components](https://vuejs.org/v2/guide/components.html)

### Przyk³ad:

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

- Stwórz prosty komponent rodzica i komponent dziecka.

### Zaawansowane zadanie:

- Stwórz bardziej z³o¿on¹ hierarchiê komponentów z przekazywaniem danych miêdzy nimi.
