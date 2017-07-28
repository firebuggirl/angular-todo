# TodoApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.0.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive/pipe/service/class/module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

Sitepoint ToDo Tutorial:

https://www.sitepoint.com/angular-2-tutorial/

Angular CLI makes it super simple to deploy our application to GitHub Pages with a single command like this:

$ ng github-pages:deploy --message 'deploy(dist): deploy on GitHub pages'

Services registered in AppComponent are only available to AppComponent and its component tree. Services registered in AppModule are available to all components in the entire application.


## To deploy an Angular 2 app with the Angular CLI to Heroku:

https://angular-cli-heroku.herokuapp.com/

* Create a Heroku account
* Install the Heroku CLI
* Create a Heroku app in your project directory with heroku create
* Move the angular-cli dependency from devDependencies to dependencies in your package.json

* Create a postinstall script in your package.json which builds your project to a dist directory on your server: ng build --aot -prod

* Install express: npm install express --save

* Create a server.js file in the root of your project and add code to serve the static files in your dist directory

* Commit your work and push it to Heroku to deploy: git push heroku master
