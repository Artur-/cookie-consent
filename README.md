![Bower version](https://img.shields.io/bower/v/vaadin-cookie-consent.svg)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/vaadin/vaadin-cookie-consent)
[![Build Status](https://travis-ci.org/vaadin/vaadin-cookie-consent.svg?branch=master)](https://travis-ci.org/vaadin/vaadin-cookie-consent)
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/vaadin/web-components?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

# &lt;vaadin-cookie-consent&gt;

[Live Demo ↗](https://vaadin.com/components/vaadin-cookie-consent/html-examples)
|
[API documentation ↗](https://vaadin.com/components/vaadin-cookie-consent/html-api)


[&lt;vaadin-cookie-consent&gt;](https://vaadin.com/components/vaadin-cookie-consent) is a [Polymer 2](http://polymer-project.org) element providing &lt;element-functionality&gt;, part of the [Vaadin components](https://vaadin.com/components).

<!--
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="vaadin-cookie-consent.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<vaadin-cookie-consent>
  ...
</vaadin-cookie-consent>
```

[<img src="https://raw.githubusercontent.com/vaadin/vaadin-cookie-consent/master/screenshot.png" width="200" alt="Screenshot of vaadin-cookie-consent">](https://vaadin.com/components/vaadin-cookie-consent)


## Getting Started

Vaadin components use the Lumo theme by default.

## The file structure for Vaadin components

- `src/component-name.html`

  Unstyled component.

- `theme/lumo/component-name.html`

  Component with Lumo theme.

- `component-name.html`

  Alias for theme/lumo/component-name.html


## Running demos and tests in browser

1. Fork the `vaadin-cookie-consent` repository and clone it locally.

1. Make sure you have [npm](https://www.npmjs.com/) installed.

1. When in the `vaadin-cookie-consent` directory, run `npm install` and then `bower install` to install dependencies.

1. Run `polymer serve --open`, browser will automatically open the component API documentation.

1. You can also open demo or in-browser tests by adding **demo** or **test** to the URL, for example:

  - http://127.0.0.1:8080/components/vaadin-cookie-consent/demo
  - http://127.0.0.1:8080/components/vaadin-cookie-consent/test


## Running tests from the command line

1. When in the `vaadin-cookie-consent` directory, run `polymer test`


## Following the coding style

We are using [ESLint](http://eslint.org/) for linting JavaScript code. You can check if your code is following our standards by running `gulp lint`, which will automatically lint all `.js` files as well as JavaScript snippets inside `.html` files.


## Contributing

  - Make sure your code is compliant with our code linters: `gulp lint`
  - Check that tests are passing: `polymer test`
  - [Submit a pull request](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github) with detailed title and description
  - Wait for response from one of Vaadin components team members


## License

Apache License 2.0
