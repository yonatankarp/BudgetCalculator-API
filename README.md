[![Build Status](https://travis-ci.org/yonatankarp/BudgetCalculator-API.svg?branch=master)](https://travis-ci.org/yonatankarp/BudgetCalculator-API)

# BudgetCalculator-API
OpenAPI definition for BudgetCalculator project

# Setting up
#### Linting
The definitions are linted with [spectral](https://github.com/stoplightio/spectral) and [travis-ci](https://travis-ci.org/). The CI lints on every push / PR.

# install dependencies
You can install the linter locally be running any of the following commands:
```
$ npm install -g @stoplight/spectral

# OR

$ yarn global add @stoplight/spectral
```

# run the lint script
In order to run the liner you should execute the following command:
```
$ spectral lint ./api/*/*.yaml

# OR

$ yarn lint
```
