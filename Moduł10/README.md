# Modu� 10: Dodatkowe biblioteki i narz�dzia
# Modu� 10: Dodatkowe biblioteki i narz�dzia

## Lekcja 1: PrimeVue - Komponenty UI

### Teoria:

- PrimeVue: Biblioteka komponent�w UI dla Vue.js.

  - Dokumentacja: [PrimeVue Documentation](https://www.primefaces.org/primevue/)

### Przyk�ad:

`js

import { createApp } from 'vue';

import App from './App.vue';

import PrimeVue from 'primevue/config';

import Button from 'primevue/button';



const app = createApp(App);

app.use(PrimeVue);

app.component('Button', Button);

app.mount('#app');



### Proste zadanie:

- Zainstaluj i skonfiguruj PrimeVue w swoim projekcie.

### Zaawansowane zadanie:

- Dodaj kilka komponent�w PrimeVue do swojej aplikacji, np. przyciski, tabele, formularze.
