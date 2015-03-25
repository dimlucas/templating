# aurelia-templating

This library is part of the [Aurelia](http://www.aurelia.io/) platform and contains an extensible HTML templating engine supporting databinding, custom elements, attached behaviors and more.

> To keep up to date on [Aurelia](http://www.aurelia.io/), please visit and subscribe to [the official blog](http://blog.durandal.io/). If you have questions, we invite you to join us on [![Join the chat at https://gitter.im/aurelia/discuss](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/aurelia/discuss?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge).

## Polyfills

* Depending on target browser(s), [core-js](https://github.com/zloirock/core-js) is likely required for `Promise` support.

* If targeting IE, [aurelia-html-template-element](https://github.com/aurelia/html-template-element) is required.

## Dependencies

* [aurelia-metadata](https://github.com/aurelia/metadata)
* [aurelia-task-queue](https://github.com/aurelia/task-queue)
* [aurelia-binding](https://github.com/aurelia/binding)
* [aurelia-loader](https://github.com/aurelia/loader)
* [aurelia-dependency-injection](https://github.com/aurelia/dependency-injection)
* [aurelia-logging](https://github.com/aurelia/logging)
* [aurelia-path](https://github.com/aurelia/path)

## Used By

* [aurelia-framework](https://github.com/aurelia/framework)
* [aurelia-templating-binding](https://github.com/aurelia/templating-binding)
* [aurelia-templating-resources](https://github.com/aurelia/templating-resources)
* [aurelia-templating-router](https://github.com/aurelia/templating-router)
* [aurelia-animator-css](https://github.com/aurelia/animator-css)

## Platform Support

This library can be used in the **browser** only.

## Building The Code

To build the code, follow these steps.

1. Ensure that [NodeJS](http://nodejs.org/) is installed. This provides the platform on which the build tooling runs.
2. From the project folder, execute the following command:

  ```shell
  npm install
  ```
3. Ensure that [Gulp](http://gulpjs.com/) is installed. If you need to install it, use the following command:

  ```shell
  npm install -g gulp
  ```
4. To build the code, you can now run:

  ```shell
  gulp build
  ```
5. You will find the compiled code in the `dist` folder, available in three module formats: AMD, CommonJS and ES6.

6. See `gulpfile.js` for other tasks related to generating the docs and linting.

## Running The Tests

To run the unit tests, first ensure that you have followed the steps above in order to install all dependencies and successfully build the library. Once you have done that, proceed with these additional steps:

1. Ensure that the [Karma](http://karma-runner.github.io/) CLI is installed. If you need to install it, use the following command:

  ```shell
  npm install -g karma-cli
  ```
2. Ensure that [jspm](http://jspm.io/) is installed. If you need to install it, use the following commnand:

  ```shell
  npm install -g jspm
  ```
3. Install the client-side dependencies with jspm:

  ```shell
  jspm install
  ```

4. You can now run the tests with this command:

  ```shell
  karma start
  ```
