# layout.css

Wrapper around flexbox to make doing flexbox layouts simple and intuitive.

## Example

```html
<div layout="horizontal reverse justified around">
  <div flex="top">A</div>
  <div flex="middle">B</div>
  <div flex="bottom">C</div>
</div>
```

## Installation

```
npm install layout.css
```

Check out [www-bundle](https://github.com/lapwinglabs/www-bundle) to see how we bundle our front-end together.

## Documentation

You can see how most of the properties work here: https://www.polymer-project.org/0.5/docs/polymer/layout-attrs.html

The difference between the polymer project and this project is that this project merges the attributes into one string. It also has support for `data-*` attributes that allow it to work with React.

## Credits

layout.css is largely based on the work done by the [Polymer team](https://www.polymer-project.org).

## License

MIT
