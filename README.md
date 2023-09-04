# Metronoid

A minimalistic metronome webpage because I need one and Google metronome is too basic.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.2.1.

# Why overkilling it with Angular?

Well, first of all because it's a great way to learn how components interact with each others! You need to watch the changes to the tempo value, and set other components accordingly.

## A preliminary roadmap

Another reason of using Angular is because **I plan to extend Metronoid and make it something more useful**, for example implementing a music sheet along side the metronome to play your favourite pieces of music with a custom tempo! It shouldn't be too hard, I've just got to figure out if I want to use an existing library (e.g. [alphaTab](https://github.com/CoderLine/alphaTab)) or make my own (which is another overkill! In case you didn't already figure it out, I love trying to do stuff myself and explore how it's done this way).

Metronoid roadmap:

- Metronome
  - range input to change tempo 10 by 10 👩‍💻
  - text input to change tempo with custom values 👩‍💻
  - implement the metronome algorithm with high sound precision (see [this repo](https://github.com/cwilso/metronome/) for reference) for quarter notes. 🧪
  - make a visual representation of the tempo
  - implement others resolution of the tempo algorithm + visuals
- _Music sheet extension - TBD_
  - _study what libraries could be used, is it worth trying to solo it? Too much effort?_

Legend:

- 👩‍💻 = currently implementing
- 🧪 = researching / study of doability

# Getting started

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
