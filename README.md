*This repository is a mirror of the [component](http://component.io) module [kenkouot/namespacer](http://github.com/kenkouot/namespacer). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/kenkouot-namespacer`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# Namespacer

    Convenient utility function for application namespacing

## Installation

    $ component install kenkouot/namespacer

## Example

```js
// Initialize to {} with a single argument
namespacer('app.foo.bar');

// Or explicitly declare your namespaces separately as the second argument
namespacer('foo.bar', 'app');

// Or an instantiated object
var app = window.app || {};
namespacer('foo.bar', app);

// Pass in a value aka app.foo.bar = { baz: 'lur' };
namespacer('foo.bar', 'app', { baz: 'lur' });
```

## API

### namespacer(str, [string || obj], [value])

## License

  MIT
