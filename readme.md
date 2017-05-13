# WpDevOps Elixir CoffeeScript Support

First ensure, that you're WpDevOps Elixir version is up to date.

## Step 1: Install

```
npm install @wpdevops\elixir-coffeescript --save-dev
```

## Step 2: Use It

```js
// Gulpfile.js

var elixir = require('laravel-elixir');

elixir(function(mix) {
    // Examples:

    mix.coffee('app.coffee');

    mix.coffee('app.coffee', 'dist/output');

    mix.coffee('app.coffee', 'dist/output/file.js');

    // https://github.com/wearefractal/gulp-coffee#options
    mix.coffee('app.coffee', 'dist/output/file.js', options);
});
```

---

This package was originally ([laravel-elixir-coffeescript](https://github.com/JeffreyWay/laravel-elixir-coffeescript)) 
written by [Jeffrey Way](https://github.com/JeffreyWay)