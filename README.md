# yaml-frontmatter-loader for webpack

YAML Frontmatter loader for [webpack](http://webpack.github.io/). Converts YAML in files to JSON. You should chain it with [json-loader](https://github.com/webpack/json-loader).

## Installation

`npm install yaml-frontmatter-loader`

## Usage

[Documentation: Using loaders](http://webpack.github.io/docs/using-loaders.html)

``` javascript

var json = require("json-loader!yaml-frontmatter-loader!./file.md");
// => returns file.md as javascript object
```

## License

MIT (http://www.opensource.org/licenses/mit-license.php)
