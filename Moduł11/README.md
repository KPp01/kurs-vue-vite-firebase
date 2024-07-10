# Modu� 11: Firebase Functions
# Modu� 11: Firebase Functions

## Lekcja 1: Wprowadzenie do Cloud Functions

### Teoria:

- Firebase Functions: Jak tworzy� i wdra�a� funkcje chmurowe za pomoc� Firebase.

  - Dokumentacja: [Firebase Functions Documentation](https://firebase.google.com/docs/functions)

### Przyk�ad:

`js

const functions = require('firebase-functions');



exports.helloWorld = functions.https.onRequest((request, response) => {

  response.send('Hello from Firebase!');

});



### Proste zadanie:

- Stw�rz prost� funkcj� chmurow�, kt�ra zwraca wiadomo�� 'Hello World'.

### Zaawansowane zadanie:

- Dodaj funkcje do obs�ugi CRUD dla Firestore za pomoc� Firebase Functions.
