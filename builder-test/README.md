# BuilderTest

* project was generated -- via -- [Angular CLI](https://github.com/angular/angular-cli) version 8.0.0-beta.11

## Development server

* `ng serve`
  * run a dev server
* | browser,
  * `http://localhost:4200/`

## Build

* `ng build`
  * build artifacts | `dist/`
  * `--prod` flag
    * production build

## Running unit tests

* `ng test`
  * -- via -- [Karma](https://karma-runner.github.io)

## Running end-to-end tests

* `ng e2e`
  * -- via -- [Protractor](http://www.protractortest.org/)

## Touch
* -- via -- "example/command-runner:command"
* see [angular.json](angular.json)
* steps to run
  * `npm install --force`
  * | "command-builder",
    * `npm run build`
  * `ng run builder-test:touch`
    * != `ng touch`
      * Reason: 🧠it's a custom builder 🧠
