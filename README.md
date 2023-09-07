# PasswordGenerator

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.0.5.

Angular Password Generator: A Deep Dive into Angular Fundamentals

The Password Generator application offers both a functional tool and an illustrative demonstration of Angular's core principles:

Interpolation: With interpolation, the {{ generatedPassword }} placeholder fluidly updates, showcasing the live password generation process.

Property Binding: Utilize the slider to set the password's length and see how [value]="passwordLength" ensures the interface reflects the user's exact preference.

Event Binding: The "Generate Password" button, powered by (click)="generatePassword()", is more than just responsive. It actively crafts a password based on user specifications, highlighting the might of event-driven design.

Structural Directives: Explore Angular's capability in dynamic content display. The advanced settings, steered by the *ngIf directive, presents users with a conditional view, exemplifying how Angular adeptly alternates UI components in response to user actions or data conditions.

Whether you aim to create a secure password or delve deep into Angular's foundational techniques, our application offers a comprehensive, enlightening experience

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
