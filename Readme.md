*This repository is a mirror of the [component](http://component.io) module [component/clone](http://github.com/component/clone). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-clone`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# clone

  Object clone supporting `date`, `regexp`, `array` and `object` types.

## Example

```js
var obj = clone({
  a: 'b',
  c: [
    new Date(),
    'tobi',
    'jane'
  ]
})
```

## API

### clone(obj)

  Clones `obj` recursively and returns it.

## License

MIT
