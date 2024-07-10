# Modu³ 15: CI/CD
# Modu³ 15: CI/CD

## Lekcja 1: Wprowadzenie do CI/CD

### Teoria:

- CI/CD: Continuous Integration i Continuous Deployment - procesy automatyzacji budowania, testowania i wdra¿ania aplikacji.

  - Dokumentacja: [GitHub Actions](https://docs.github.com/en/actions)

### Przyk³ad:

`yaml

name: CI/CD Pipeline



on:

  push:

    branches: [ main ]



jobs:

  build:

    runs-on: ubuntu-latest



    steps:

    - name: Checkout code

      uses: actions/checkout@v2



    - name: Set up Node.js

      uses: actions/setup-node@v2

      with:

        node-version: '14'



    - name: Install dependencies

      run: npm install



    - name: Build frontend

      run: npm run build



    - name: Deploy to Firebase

      env:



### Proste zadanie:

- Skonfiguruj prosty pipeline CI/CD dla swojego projektu.

### Zaawansowane zadanie:

- Zaimplementuj pe³ny pipeline CI/CD z automatycznym testowaniem i wdra¿aniem aplikacji.
