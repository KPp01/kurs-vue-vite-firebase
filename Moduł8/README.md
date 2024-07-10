# Modu³ 8: Zarz¹dzanie stanem z Vuex
# Modu³ 8: Zarz¹dzanie stanem z Vuex

## Lekcja 1: Wprowadzenie do Vuex

### Teoria:

- Vuex: Centralny magazyn stanu dla aplikacji Vue.js, który umo¿liwia zarz¹dzanie stanem na poziomie globalnym.

  - Dokumentacja: [Vuex Documentation](https://vuex.vuejs.org/)

### Przyk³ad:

`js

import { createStore } from 'vuex';



const store = createStore({

  state () {

    return {

      count: 0

    }

  },

  mutations: {

    increment (state) {

      state.count++

    }

  }

});



export default store;



### Proste zadanie:

- Skonfiguruj Vuex w swoim projekcie Vue.

### Zaawansowane zadanie:

- Dodaj akcje i modu³y do zarz¹dzania bardziej z³o¿onym stanem aplikacji.
