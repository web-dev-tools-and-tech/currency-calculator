# currency-calculator

Application that yada yada yada.

## Installing

* This package is meant to be used as a docker container, passing the environment variables as defined below.

```sh
docker run -d applitools/currency-calculator
```

* Alternatively, it can be run using `./scripts/run-currency-calculator.js`,
  passing the environment variables as defined below.

```sh
npm install -g @applitools/currency-calculator
run-currency-calculator.js
```

* Alternatively, you can import it and create the app (see below), passing it the configuration as defined below.

```sh
npm install @applitools/currency-calculator
```

## Services it depends on

* Yada: yada yada

### Queue Job Schema

A JSON with the following fields:

* `yada`: yada yada

## Environment variables needed by docker container and application

* `YADA_YADA`: yada

## Using the package to run the application

```js
const createApp = require('@applitools/currency-calculator')

// configuration options aee the same as the above corresponding environment variables
const app = createApp({})

// app is an express app. Use listen to start it in the usual way
app.listen(/*...*/)
```
