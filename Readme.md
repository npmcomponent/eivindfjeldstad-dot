*This repository is a mirror of the [component](http://component.io) module [eivindfjeldstad/dot](http://github.com/eivindfjeldstad/dot). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/eivindfjeldstad-dot`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# dot

  Get and set object properties with dot notation

## Installation

    $ component install eivindfjeldstad/dot

## API

### dot.set(object, path, value)
```js
dot.set(obj, 'cool.aid', 'rocks');
assert(obj.cool.aid === 'rocks');
```

### dot.get(object, path)
```js
var value = dot.get(obj, 'cool.aid');
assert(value === 'rocks');
```

## License

  MIT
