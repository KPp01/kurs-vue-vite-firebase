# Modu� 8: Zarz�dzanie stanem z Vuex
# Modu� 8: Zarz�dzanie stanem z Vuex

## Lekcja 1: Wprowadzenie do Vuex

### Teoria:

- Vuex: Centralny magazyn stanu dla aplikacji Vue.js, kt�ry umo�liwia zarz�dzanie stanem na poziomie globalnym.

  - Dokumentacja: [Vuex Documentation](https://vuex.vuejs.org/)

### Przyk�ad:

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

- Dodaj akcje i modu�y do zarz�dzania bardziej z�o�onym stanem aplikacji.
