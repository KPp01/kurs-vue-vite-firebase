# Modu³ 7: Firestore
# Modu³ 7: Firestore

## Lekcja 1: Konfiguracja Firestore

### Teoria:

- Firestore: Jak skonfigurowaæ Firestore w projekcie Vue.

  - Dokumentacja: [Firestore Documentation](https://firebase.google.com/docs/firestore)

### Przyk³ad:

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

- Stwórz funkcje do dodawania, edytowania i usuwania dokumentów w Firestore.
