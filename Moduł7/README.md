# Modu� 7: Firestore
# Modu� 7: Firestore

## Lekcja 1: Konfiguracja Firestore

### Teoria:

- Firestore: Jak skonfigurowa� Firestore w projekcie Vue.

  - Dokumentacja: [Firestore Documentation](https://firebase.google.com/docs/firestore)

### Przyk�ad:

`js

import { getFirestore, collection, getDocs } from 'firebase/firestore';



const db = getFirestore();

const querySnapshot = await getDocs(collection(db, 'users'));

querySnapshot.forEach((doc) => {

  console.log(${doc.id} => );

});



### Proste zadanie:

- Skonfiguruj Firestore w swoim projekcie Vue.

### Zaawansowane zadanie:

- Stw�rz funkcje do dodawania, edytowania i usuwania dokument�w w Firestore.
