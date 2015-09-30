
# metalsmith-congregate

  Bring multiple separate files to one location.

## CLI Usage

  metalsmith-congregate has not yet been tested with Metalsmith's CLI configuration

## Javascript Usage

  metalsmith-congregate is based off of metalsmith-assets, and thus uses similarly-named options. 
  
```js
var congregate = require('metalsmith-congregate');

metalsmith.use(congregate({
  source: [ // an array of file paths relative to the working directory
    "./node_modules/jquery/dist/jquery.js", 
    "./node_modules/bootstrap/dist/js/bootstrap.js"
  ],
  destination: './assets' // relative to the build directory
}));
```

## License

  MIT
