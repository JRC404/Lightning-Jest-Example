# Jest Test Application

## com.credersi.app.JestTestApplication

### Getting started

> Before you follow the steps below, make sure you have the
[Lightning-CLI](https://rdkcentral.github.io/Lightning-CLI/#/) installed _globally_ only your system

```
npm install -g @lightningjs/cli
```

#### Running the App

1. Install the NPM dependencies by running `npm install`

2. Build the App using the _Lightning-CLI_ by running `lng build` inside the root of your project

3. Fire up a local webserver and open the App in a browser by running `lng serve` inside the root of your project

#### Developing the App

- use `lng dev` to start the watcher and run a local webserver / open the App in a browser _at the same time_

#### Testing the App

The application uses Jest to test applications. After you have installed the dependencies, you should be able to run the following command:

1. `npm test`

This should at first, return 2 successful tests in one Test Suite.

#### Documentation

* Use `lng docs` to open up the Lightning-SDK documentation.
* Jest documentation can be found here: [Jest Documentation](https://jestjs.io/docs/getting-started)
