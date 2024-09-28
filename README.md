# CalcualtorProject

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.1.2.

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

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.









This is a simple calculator  satic web application built using Angular. It allows users to input numbers and basic arithmetic operations and get a result.
The project includes basic functionalities like addition, subtraction, multiplication, division, and clearing the display.

Features


Basic arithmetic operations (addition, subtraction, multiplication, division)
Clear button to reset the calculator display
Backspace function to remove the last entered character
Prevents invalid input like multiple leading zeros
Automatically resets the display when a new input is entered after a result.


Technologies Used


Angular: Framework for building the user interface and handling component logic.
Standalone Components: Used to build the AppComponent with Angular's standalone API.
FormsModule: For handling forms and input bindings.
SSR: Server-Side Rendering compatibility using PLATFORM_ID to detect browser environments. 
