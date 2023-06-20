A simple Cypress Framework Definition for Analog.JS

See [the documentation](https://docs.cypress.io/guides/component-testing/third-party-definitions#List-of-Framework-Definitions) to learn how to author a Framework Definition for your favorite library!

In your Analog.js project:

1. npm install cypress cypress-ct-analog
2. At the top of your `cypress/support/component.ts` add `import '@angular/compiler'`
3. Run `cypress open` and select AnalogJS as the framework. Cypress will do the rest.

