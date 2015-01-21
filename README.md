# CSS FILTER CONTRAST

  Mobile-first classes for css-filter-contrast.
  Set the desired css-filter-contrast on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-filter-contrast
```
View on [npm](https://www.npmjs.org/package/css-filter-contrast)


## File Size

1.1K filter-contrast.css
948B filter-contrast.min.css
207B minified and gzipped

## The Code
```
.contrast0 { filter: contrast(0); }
.contrast1 { filter: contrast(50%); }
.contrast2 { filter: contrast(75%); }
.contrast3 { filter: contrast(100%); }
.contrast4 { filter: contrast(150%); }
.contrast5 { filter: contrast(200%); }

@media screen and (min-width: 48em) {
  .contrast0-ns { filter: contrast(0); }
  .contrast1-ns { filter: contrast(50%); }
  .contrast2-ns { filter: contrast(75%); }
  .contrast3-ns { filter: contrast(100%); }
  .contrast4-ns { filter: contrast(150%); }
  .contrast5-ns { filter: contrast(200%); }

}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .contrast0-m { filter: contrast(0); }
  .contrast1-m { filter: contrast(50%); }
  .contrast2-m { filter: contrast(75%); }
  .contrast3-m { filter: contrast(100%); }
  .contrast4-m { filter: contrast(150%); }
  .contrast5-m { filter: contrast(200%); }

}

@media screen and (min-width: 64em)  {
  .contrast0-l { filter: contrast(0); }
  .contrast1-l { filter: contrast(50%); }
  .contrast2-l { filter: contrast(75%); }
  .contrast3-l { filter: contrast(100%); }
  .contrast4-l { filter: contrast(150%); }
  .contrast5-l { filter: contrast(200%); }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2015 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

