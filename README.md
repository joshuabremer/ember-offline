# Ember-offline

Show notification on Ember app when user goes offline.

## Demo

Check out the demo on [github pages](https://ahmadsoe.github.io/ember-offline/ "Ember-offline demo").

## Installation

`ember install ember-offline`

Want to customize your Offline.js settings? Ember-Offline inherits the Offline.options from the environment.js file. Add an `emberOptions` key to the environment.js to pass any additional options:

### Example:

````
var ENV = {
  ...
  emberOffline: {
    themes: {
      theme: 'default',
      indicator: false,
      language: 'english'
    }
  }
  ...
};
````

See here for more options: http://github.hubspot.com/offline/

## Running

* `ember server`
* Visit your app at http://localhost:4200.

## Running Tests

* `ember test`
* `ember test --server`

## Building

* `ember build`

For more information on using ember-cli, visit [http://www.ember-cli.com/](http://www.ember-cli.com/).
