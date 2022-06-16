# vue-app

This template should help get you started developing with Vue 3 in Vite.

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Customize configuration

See [Vite Configuration Reference](https://vitejs.dev/config/).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```

### Run Unit Tests with [Vitest](https://vitest.dev/)

```sh
npm run test:unit
```

### Run End-to-End Tests with [Cypress](https://www.cypress.io/)

```sh
npm run build
npm run test:e2e # or `npm run test:e2e:ci` for headless testing
```

### Lint with [ESLint](https://eslint.org/)

```sh
npm run lint
```


### Run docker 
```
docker run -d -p8080:8080 jenkins/jenkins
docker ps 
docker exec -it 08be58d4be84 bash

cat /var/jenkins_home/secrets/initialAdminPassword
```

###
```
npm i -D semantic-release @semantic-release/{git,commit-analyzer,release-notes-generator,npm,changelog}

npm i -D cz-conventional-changelog

npm i -D commitizen 
commitizen init cz-conventional-changelog --save-dev --save-exact

```
