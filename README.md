# Ember-sinon

This addon adds support for [Sinon](https://github.com/cjohansen/Sinon.JS) to assist in testing your Ember CLI app.

## Installation

If you are using Ember CLI 0.1.5 or higher:

```
ember install:addon ember-sinon
```

otherwise:

```
npm install --save-dev ember-sinon
ember g ember-sinon
```

## Usage

While in testing mode (i.e. either when visiting `/tests` or when running `ember test`), `sinon` will be available in the global namespace.
