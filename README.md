# Fullstack Boilerplate

 

## Contents

- [Backend service](app-backend) - a Java/Spring Boot service with a `/ping` endpoint. Extend with your code.
- [Frontend app](app-frontend) - a React app. Extend with your code.
- [E2E test suites](cypress/integration) - a backend and a frontend Cypress test suites. Extend with your tests.
- [Pipeline](.github/workflows/tests.yml) - a test Runner that executes the Cypress tests on push to a branch other than `master`/`main`.

## Tech Stack

### Backend

- Java 17
- Spring Boot 2
- SQLite 3
- Gradle 7
  
### Frontend

- React
- Typescript 

### Misc

- Cypress
- GitHub Actions

## Getting started

1. Make sure the required version of Java (17) is configured on your local env.

2. Make sure npm & node are configured on your local env. You can download those distributions for your platform [here](https://nodejs.org/en/download/)

3. Build your app.

```bash
npm install
npm run build # both Java/Spring Boot backend and Vue frontend
npm run build:backend # only Java/Spring Boot backend
npm run build:frontend # only React frontend
```

4. Start your app.

```bash
npm install
npm run start # both Java/Spring Boot backend and Vue frontend
npm run start:backend # only Java/Spring Boot backend
npm run start:frontend # only React frontend
```

5. Run the Cypress tests.

```bash
npm run test # run project tests under `cypress/integration`
```

---


Did you find this repo useful? **Give me a shout on  / [LinkedIn](https://www.linkedin.com/in/garfield-heron-404577/)**.
