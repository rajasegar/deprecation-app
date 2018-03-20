# deprecation-app [![Build Status](https://travis-ci.org/ember-learn/deprecation-app.svg?branch=master)](https://travis-ci.org/ember-learn/deprecation-app)

This is the app that serves https://emberjs.com/deprecations/

## Adding new deprecations

To add a new deprecation, you can use the `ember generate deprecation` command. For example, the following command:

```bash
ember generate ember/v3/deprecate-logger
```

Would generate a new deprecation in the appropriate sub-folder of [content](https://github.com/ember-learn/deprecation-app/tree/master/content/) for the Ember v3.0.0 deprecation of `Ember.Logger`. folder contains all the deprecations that are listed by the website. You can see [this sample](https://raw.githubusercontent.com/ember-learn/deprecation-app/master/content/ember/v3/getting-each.md) for reference.

## Prerequisites

You will need the following things properly installed on your computer.

* [Git](https://git-scm.com/)
* [Node.js](https://nodejs.org/) (with npm)
* [Ember CLI](https://ember-cli.com/)
* [Google Chrome](https://google.com/chrome/)

## Installation

* `git clone <repository-url>` this repository
* `cd deprecation-app`
* `npm install` / `yarn`

## Running / Development

* `ember serve`
* Visit your app at [http://localhost:4200/ember/v2.x](http://localhost:4200/ember/v2.x).
* Visit your tests at [http://localhost:4200/tests](http://localhost:4200/tests).

## Troubleshooting

Do you only see a blank page with a header and footer? Or maybe a 404? Make sure to visit
[http://localhost:4200/ember/v2.x](http://localhost:4200/ember/v2.x) to view the app
with data loaded in.

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
