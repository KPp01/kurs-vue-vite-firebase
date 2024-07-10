# Modu� 13: Testowanie end-to-end (E2E)
# Modu� 13: Testowanie end-to-end (E2E)

## Lekcja 1: Wprowadzenie do Cypress

### Teoria:

- Cypress: Narz�dzie do testowania end-to-end aplikacji webowych.

  - Dokumentacja: [Cypress Documentation](https://docs.cypress.io/)

### Przyk�ad:

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

- Stw�rz prosty test E2E dla swojej aplikacji z u�yciem Cypress.

### Zaawansowane zadanie:

- Napisz zestaw test�w E2E dla g��wnych funkcji swojej aplikacji.
