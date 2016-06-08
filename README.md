## angulartics-webtrends-analytics

[![NPM version][npm-image]][npm-url] [![NPM downloads][npm-downloads-image]][npm-downloads-url] [![Bower version][bower-image]][bower-url] [![Dependencies status][dep-status-image]][dep-status-url] [![MIT license][license-image]][license-url] [![Gitter Chat][gitter-image]][gitter-url]

Webtrends Analytics plugin for [Angulartics](https://github.com/angulartics/angulartics).

## Install

First make sure you've read installation and setup instructions for [Angulartics](https://github.com/angulartics/angulartics).

*Note*: This plugin requires that you have an Analytics account with Webtrends, and have been allocated a DCSID or Infinity Tag ID.

Then you can install this package either with `npm` or with `bower`.

### npm

```shell
npm install angulartics-webtrends-analytics
```

Then add `angulartics.webtrends.analytics` as a dependency for your app:

```javascript
require('angulartics')

angular.module('myApp', [
  'angulartics',
  require('angulartics-webtrends-analytics')
]);
```

> Please note that core Angulartics doesn't export the name yet, but it will once we move it into [the new organization](http://github.com/angulartics).

### bower

```shell
bower install angulartics-webtrends-analytics
```

Add the `<script>` to your `index.html`:

```html
<script src="/bower_components/angulartics-webtrends-analytics/dist/angulartics-webtrends-analytics.min.js"></script>
```

Then add `angulartics.webtrends.analytics` as a dependency for your app:

```javascript
angular.module('myApp', [
  'angulartics',
  'angulartics.webtrends.analytics'
]);
```

## Documentation

Documentation is available on the [Angulartics site](http://angulartics.github.io/).


## Contributing

If you use Webtrends Analytics and want to contribute with code/documentation/examples, please submit a pull request or open an issue.

## Development

```shell
npm run build
```

## License

[MIT](LICENSE)

[npm-image]: https://img.shields.io/npm/v/angulartics-webtrends-analytics.svg
[npm-url]: https://npmjs.org/package/angulartics-webtrends-analytics
[npm-downloads-image]: https://img.shields.io/npm/dm/angulartics-webtrends-analytics.svg
[npm-downloads-url]: https://npmjs.org/package/angulartics-webtrends-analytics
[bower-image]: https://img.shields.io/bower/v/angulartics-webtrends-analytics.svg
[bower-url]: http://bower.io/search/?q=angulartics-webtrends-analytics
[dep-status-image]: https://img.shields.io/david/angulartics/angulartics-webtrends-analytics.svg
[dep-status-url]: https://david-dm.org/angulartics/angulartics-webtrends-analytics
[license-image]: http://img.shields.io/badge/license-MIT-blue.svg
[license-url]: LICENSE
[gitter-image]: https://img.shields.io/gitter/room/nwjs/nw.js.svg
[gitter-url]: https://gitter.im/angulartics
