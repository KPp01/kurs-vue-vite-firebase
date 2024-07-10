# Module 15: CI/CD

## Lesson 1: Introduction to CI/CD

### Theory:

- **CI/CD**: Continuous Integration and Continuous Deployment - automating the building, testing, and deploying of applications.

  - Documentation: [GitHub Actions](https://docs.github.com/en/actions)

### Example:

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

      run: firebase deploy --token $`{{ secrets.FIREBASE_TOKEN }} 

      env:

        FIREBASE_TOKEN: $`{{ secrets.FIREBASE_TOKEN }} 

` 

### Step-by-step Task:

1. Set up a simple CI/CD pipeline for your project using GitHub Actions.

2. Add steps for building and testing your application.

3. Deploy your application to Firebase Hosting using the CI/CD pipeline.

### Detailed Task:

Create a CI/CD pipeline with automated testing and deployment for your project.

### Advanced Task:

Develop a comprehensive CI/CD pipeline that includes code quality checks, automated testing, and deployment to multiple environments.

