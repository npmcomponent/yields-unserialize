*This repository is a mirror of the [component](http://component.io) module [yields/unserialize](http://github.com/yields/unserialize). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yields-unserialize`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# unserialize

  Unserialize a serialized javascript value.

## Installation

    $ component install yields/unserialize

## Example

```js
var str = JSON.stringify('boo');
assert('boo' == unserialize(str));
```

## License

  MIT
