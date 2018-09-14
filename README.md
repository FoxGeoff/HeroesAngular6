# HeroesAngular6

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.1.5.

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

## Check: Add Observable HeroService:
Angular 6 syntax - ```import { Observable, of } from 'rxjs';```

## Check: Show messages

## Check Add routing module
Run ```ng generate module app-routing --flat --module=app```

You generally don't declare components in a routing module so you can delete the @NgModule.declarations array and delete CommonModule references too.
You'll configure the router with Routes in the RouterModule so import those two symbols from the @angular/router library.
Add an @NgModule.exports array with RouterModule in it. Exporting RouterModule makes router directives available for use in the AppModule components that will need them.

## Check Update routing module

## Check: Add routes and <router-outlet></router-outlet>

