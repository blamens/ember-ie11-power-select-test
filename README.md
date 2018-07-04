# ember-ie11-power-select-test

Check out the difference between IE11 and other browsers on:
https://ember-ie11-power-select-test.herokuapp.com/

To test this:

* `git clone <repository-url>` this repository
* `cd ie11-power-select-test`
* `yarn; ember s`

You will see that all the power selects are opened by default in Internet Explorer 11 (all other browser do not open them).

* `open package.json and change ember-source to 3.0.0 `
* `rimraf dist tmp node_modules yarn.lock; yarn; ember s`

If you open up the app in Internet Explorer 11 now, you will see that the power selects are all closed.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with NPM)
* [Ember CLI](https://ember-cli.com/)
* [Google Chrome](https://google.com/chrome/)

## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200](http://localhost:4200).
* Visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* `ember test`
* `ember test --server`

### Building

* `ember build` (development)
* `ember build --environment production` (production)

### Deploying

Specify what it takes to deploy your app.

## Further Reading / Useful Links

* [ember.js](https://emberjs.com/)
* [ember-cli](https://ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
  * [ember inspector for firefox](https://addons.mozilla.org/en-US/firefox/addon/ember-inspector/)
