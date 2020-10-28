# MyAngularDesigncourse

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.1.6.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).


*****************************************************************

Mehr: https://coursetro.com/posts/code/174/Angular-8-Tutorial-&-Crash-Course

API: https://api.openbrewerydb.org/breweries

********************************************************************

Deployment

Let's say that we're happy with our app and we want to deploy it.

We first have to create a production build with the Angular CLI. Visit the console and issue the following command:

> ng build --prod

This will create a /dist folder. We can even run it locally with something like lite-server. To install lite-server:

> npm i -g lite-server

Hop into the folder: myapp\dist\myapp\ and run:

> lite-server

This will launch the production build in the browser!

At this point, you have a number of options for deploying it (Github Pages, Netlify, your own hosting, etc..).
