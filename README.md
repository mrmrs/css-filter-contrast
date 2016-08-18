# css-filter-contrast 0.0.7

Css module of single purpose classes for filter contrast

#### Stats

241 | 24 | 24
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-filter-contrast
```

#### With Git

```
git clone https://github.com/tachyons-css/css-filter-contrast
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-filter-contrast";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-filter-contrast">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   FILTER CONTRAST
*/
.contrast0 { filter: contrast( 0 ); }
.contrast1 { filter: contrast( 50% ); }
.contrast2 { filter: contrast( 75% ); }
.contrast3 { filter: contrast( 100% ); }
.contrast4 { filter: contrast( 150% ); }
.contrast5 { filter: contrast( 200% ); }
@media screen and (min-width: 48em) {
 .contrast0-ns { filter: contrast( 0 ); }
 .contrast1-ns { filter: contrast( 50% ); }
 .contrast2-ns { filter: contrast( 75% ); }
 .contrast3-ns { filter: contrast( 100% ); }
 .contrast4-ns { filter: contrast( 150% ); }
 .contrast5-ns { filter: contrast( 200% ); }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .contrast0-m { filter: contrast( 0 ); }
 .contrast1-m { filter: contrast( 50% ); }
 .contrast2-m { filter: contrast( 75% ); }
 .contrast3-m { filter: contrast( 100% ); }
 .contrast4-m { filter: contrast( 150% ); }
 .contrast5-m { filter: contrast( 200% ); }
}
@media screen and (min-width: 64em) {
 .contrast0-l { filter: contrast( 0 ); }
 .contrast1-l { filter: contrast( 50% ); }
 .contrast2-l { filter: contrast( 75% ); }
 .contrast3-l { filter: contrast( 100% ); }
 .contrast4-l { filter: contrast( 150% ); }
 .contrast5-l { filter: contrast( 200% ); }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
