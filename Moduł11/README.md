# Modu³ 11: Firebase Functions
# Modu³ 11: Firebase Functions

## Lekcja 1: Wprowadzenie do Cloud Functions

### Teoria:

- Firebase Functions: Jak tworzyæ i wdra¿aæ funkcje chmurowe za pomoc¹ Firebase.

  - Dokumentacja: [Firebase Functions Documentation](https://firebase.google.com/docs/functions)

### Przyk³ad:

`js

const functions = require('firebase-functions');



exports.helloWorld = functions.https.onRequest((request, response) => {

  response.send('Hello from Firebase!');

});



### Proste zadanie:

- Stwórz prost¹ funkcjê chmurow¹, która zwraca wiadomoœæ 'Hello World'.

### Zaawansowane zadanie:

- Dodaj funkcje do obs³ugi CRUD dla Firestore za pomoc¹ Firebase Functions.
