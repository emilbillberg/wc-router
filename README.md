[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/emilbillberg/wc-router)

# wc-router
A lightweight client-side router built with webcomponents.
- [Documentation](https://www.webcomponents.org/element/emilbillberg/wc-router/wc-router)
- [Demo](https://www.webcomponents.org/element/emilbillberg/wc-router/demo/demo/index.html)

## Install
```
bower install --save emilbillberg/wc-router
```

## Example
```
<wc-router main>
    <wc-path name="home" pattern="^/$"></wc-path>
    <wc-path name="signup" pattern="^/signup$"></wc-path>
    <wc-path name="schedule" pattern="^/schedule$"></wc-path>
    <wc-path name="info" pattern="^/info$"></wc-path>
</wc-router>
```

## Usage
First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally.

```
polymer serve
```

## Test
Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.

```
polymer test
```

## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License
MIT
