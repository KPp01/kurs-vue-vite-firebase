# Modu� 6: Integracja z Firebase
# Modu� 6: Integracja z Firebase

## Lekcja 1: Konfiguracja Firebase w projekcie Vue

### Teoria:

- Firebase: Jak zintegrowa� Firebase z projektem Vue.

  - Dokumentacja: [Firebase Documentation](https://firebase.google.com/docs)

### Przyk�ad:

`js

import { createApp } from 'vue';

import { initializeApp } from 'firebase/app';

import App from './App.vue';



const firebaseConfig = {

  apiKey: 'YOUR_API_KEY',

  authDomain: 'YOUR_AUTH_DOMAIN',

  projectId: 'YOUR_PROJECT_ID',

  storageBucket: 'YOUR_STORAGE_BUCKET',

  messagingSenderId: 'YOUR_MESSAGING_SENDER_ID',

  appId: 'YOUR_APP_ID'

};



initializeApp(firebaseConfig);

createApp(App).mount('#app');





### Proste zadanie:

- Skonfiguruj Firebase w swoim projekcie Vue.

### Zaawansowane zadanie:

- Dodaj obs�ug� autoryzacji u�ytkownik�w za pomoc� Firebase Authentication.
