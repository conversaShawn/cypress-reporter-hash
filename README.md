# Repro- v10 ignores name of file defined in `mochaFile`

## NOTE:
After some testing, I discovered the cypress.config.js syntax was off. 

## Instructions
`yarn`
`yarn cypress run --reporter junit --reporter-options "mochaFile=cypress/results/any_name-[hash].xml,toConsole=true"`

### [v9 branch](https://github.com/conversaShawn/cypress-reporter-hash/tree/v9)
### [v10 branch](https://github.com/conversaShawn/cypress-reporter-hash/tree/v10)