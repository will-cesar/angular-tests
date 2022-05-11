## Jasmine
[Jasmine](https://jasmine.github.io/pages/docs_home.html) is an open-source Behavior Driven Development (BDD) testing framework for Javascript.

#### Observations:
- ***f*describe**: say to Jasmine run only the test that use prefix *f*

#### Functions:
- `spyOn()` - a function to spy class methods. Check if the method was called ow not, if was called, what param is used, how many times the method was called and etc.

## Karma
[Karma](https://karma-runner.github.io/latest/index.html) is a testing tool used for running and executing Javascript code. It was created by the Angular team to make it easier to test angular applications. Karma builds a web server that executes source code from test code for each of the linked browsers. As a result, the developer can see which tests have been successful and which have failed.


## Test structure
- **describe**: a function for grouping related specifications, which takes as an argument a string describing the tested solution.
- **specs**: functions called the global `it` function, which takes as an argument a string describing the tested functionality.
- **expectations**: the `expect` function, taking a certain value that we want to check. It may contain a call to a checked function.
- **matcher**: a function that connects the checked function with the expected result. In the example above, it is `.toBe()`. There are other matchers such as `toEqual()` or `toBeTruthy()`.

## Resources
- Angular, Karma & Jasmine: Introduction to testing - https://medium.com/@matsal.dev/angular-karma-jasmine-introduction-to-testing-b9ded7d70998
- Angular Unit Testing Series:
    - Episode #1: Getting Started - https://pkerbynn.medium.com/angular-unit-testing-series-episode-1-getting-started-5ec86d645525
    - Episode #2: Introduction to Angular Unit Testing w/ Jasmine & ts-mocking-bird - https://javascript.plainenglish.io/introduction-to-angular-unit-testing-w-jasmine-ts-mocking-bird-3475a1d906e7
    - Episode #3: Component testing w/ Jasmine - https://medium.com/nerd-for-tech/angular-unit-testing-series-episode-3-component-testing-w-jasmine-2ed25082558f
- Testes Unitários no Angular - Entenda como funciona - https://www.youtube.com/watch?v=RCi2EEwNZ6M&list=WL&index=3
- Form Testing in Angular - https://medium.com/geekculture/form-testing-in-angular-116762220c4f