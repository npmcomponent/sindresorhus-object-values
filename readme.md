*This repository is a mirror of the [component](http://component.io) module [sindresorhus/object-values](http://github.com/sindresorhus/object-values). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/sindresorhus-object-values`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# object-values [![Build Status](https://travis-ci.org/sindresorhus/object-values.svg?branch=master)](https://travis-ci.org/sindresorhus/object-values)

> Get the values of an object

Returns an array of own enumerable property values of an object.


## Install

Download [manually](https://github.com/sindresorhus/object-values/releases) or with a package-manager.

```bash
$ npm install --save object-values
```

```bash
$ bower install --save object-values
```

```bash
$ component install sindresorhus/object-values
```


## Usage

```js
objectValues({foo: 0, bar: 1});
//=> [0, 1]
```


## License

[MIT](http://opensource.org/licenses/MIT) © [Sindre Sorhus](http://sindresorhus.com)
