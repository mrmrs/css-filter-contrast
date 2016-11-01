# css-filter-contrast 1.0.6

Css module of single purpose classes for filter contrast

#### Stats

281 | 24 | 48
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-filter-contrast
```

Learn more about using css installed with npm:
* https://webpack.github.io/docs/stylesheets.html
* https://github.com/defunctzombie/npm-css

#### With Git

http:
```
git clone https://github.com/tachyons-css/css-filter-contrast
```

ssh:
```
git clone git@github.com:tachyons-css/css-filter-contrast.git
```

## Usage

#### Using with [Postcss](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-filter-contrast";
```

Then process the css using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons path/to/css-file.css > dist/t.css
```

#### Using the css

##### CDN
The easiest and most simple way to use the css is to use the cdn hosted version. Include it in the head of your html with:

```
<link rel="stylesheet" href="http://unpkg.com/css-filter-contrast@1.0.6/css/css-filter-contrast.min.css" />
```

##### Locally
The built css is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-filter-contrast">
```

#### Development

The source css files can be found in the `src` directory.
Running `$ npm start` will process the source css and place the built css in the `css` directory.

## The css

```css
/*
   FILTER CONTRAST
*/
.contrast0 { -webkit-filter: contrast( 0 ); filter: contrast( 0 ); }
.contrast1 { -webkit-filter: contrast( 50% ); filter: contrast( 50% ); }
.contrast2 { -webkit-filter: contrast( 75% ); filter: contrast( 75% ); }
.contrast3 { -webkit-filter: contrast( 100% ); filter: contrast( 100% ); }
.contrast4 { -webkit-filter: contrast( 150% ); filter: contrast( 150% ); }
.contrast5 { -webkit-filter: contrast( 200% ); filter: contrast( 200% ); }
@media screen and (min-width: 48em) {
 .contrast0-ns { -webkit-filter: contrast( 0 ); filter: contrast( 0 ); }
 .contrast1-ns { -webkit-filter: contrast( 50% ); filter: contrast( 50% ); }
 .contrast2-ns { -webkit-filter: contrast( 75% ); filter: contrast( 75% ); }
 .contrast3-ns { -webkit-filter: contrast( 100% ); filter: contrast( 100% ); }
 .contrast4-ns { -webkit-filter: contrast( 150% ); filter: contrast( 150% ); }
 .contrast5-ns { -webkit-filter: contrast( 200% ); filter: contrast( 200% ); }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .contrast0-m { -webkit-filter: contrast( 0 ); filter: contrast( 0 ); }
 .contrast1-m { -webkit-filter: contrast( 50% ); filter: contrast( 50% ); }
 .contrast2-m { -webkit-filter: contrast( 75% ); filter: contrast( 75% ); }
 .contrast3-m { -webkit-filter: contrast( 100% ); filter: contrast( 100% ); }
 .contrast4-m { -webkit-filter: contrast( 150% ); filter: contrast( 150% ); }
 .contrast5-m { -webkit-filter: contrast( 200% ); filter: contrast( 200% ); }
}
@media screen and (min-width: 64em) {
 .contrast0-l { -webkit-filter: contrast( 0 ); filter: contrast( 0 ); }
 .contrast1-l { -webkit-filter: contrast( 50% ); filter: contrast( 50% ); }
 .contrast2-l { -webkit-filter: contrast( 75% ); filter: contrast( 75% ); }
 .contrast3-l { -webkit-filter: contrast( 100% ); filter: contrast( 100% ); }
 .contrast4-l { -webkit-filter: contrast( 150% ); filter: contrast( 150% ); }
 .contrast5-l { -webkit-filter: contrast( 200% ); filter: contrast( 200% ); }
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

