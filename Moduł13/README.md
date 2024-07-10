# Modu³ 13: Testowanie end-to-end (E2E)
# Modu³ 13: Testowanie end-to-end (E2E)

## Lekcja 1: Wprowadzenie do Cypress

### Teoria:

- Cypress: Narzêdzie do testowania end-to-end aplikacji webowych.

  - Dokumentacja: [Cypress Documentation](https://docs.cypress.io/)

### Przyk³ad:

`js

// example.spec.js



describe('My First Test', () => {

  it('Visits the Kitchen Sink', () => {

    cy.visit('https://example.cypress.io');

    cy.contains('type');

    cy.get('.action-email').type('fake@email.com');

  });

});



### Proste zadanie:

- Stwórz prosty test E2E dla swojej aplikacji z u¿yciem Cypress.

### Zaawansowane zadanie:

- Napisz zestaw testów E2E dla g³ównych funkcji swojej aplikacji.
