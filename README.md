# MyFlixAngularClient

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 17.1.0.


## Description

The client-side for an app called myMovie based on its existing server-side code (REST API and database).

## Dependencies

- Angular: Web application framework for building single-page client applications
- Angular Material: UI component library for Angular, implementing Google's Material Design.
- TypeDoc: Generates HTML API documentation from TypeScript code.

## Corresponding API

- Movie API: https://github.com/Luisa-Inc/movie_api
- Hosted version: https://luisa-inc.github.io/myFlix-Angular-client/welcome 

## Views

### Welcome View

- Allows users to either log in with a username and password or signup


### Main View

- Returns all movie from the API to the user
- Ability to see director details, genre details and synopsis of each movie
- in Navbar:
    - Ability to log out
    - Ability to navigate to Profile View

### Profile View

- Displays user registration details
- Allows users to update their info (username, email, date of birth)
- Allows existing users to deregister
- Displays favorite movies
    - Allows users to remove a movie from their list of favorites


# Set up

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.



