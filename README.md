# css-transition-duration 0.0.6

Css module of single purpose classes for transition duration

#### Stats

243 | 24 | 24
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-transition-duration
```

#### With Git

```
git clone https://github.com/tachyons-css/css-transition-duration
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-transition-duration";
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
<link rel="stylesheet" href="path/to/module/css/css-transition-duration">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   TRANSITION DURATION
*/
.td-1 { transition-duration: 120ms; }
.td-2 { transition-duration: .3s; }
.td-3 { transition-duration: .6s; }
.td-4 { transition-duration: 1s; }
.td-5 { transition-duration: 5s; }
.td-i { transition-duration: inherit; }
@media screen and (min-width: 48em) {
 .td-1-ns { transition-duration: 120ms; }
 .td-2-ns { transition-duration: .3s; }
 .td-3-ns { transition-duration: .6s; }
 .td-4-ns { transition-duration: 1s; }
 .td-5-ns { transition-duration: 5s; }
 .td-i-ns { transition-duration: inherit; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .td-1-m { transition-duration: 120ms; }
 .td-2-m { transition-duration: .3s; }
 .td-3-m { transition-duration: .6s; }
 .td-4-m { transition-duration: 1s; }
 .td-5-m { transition-duration: 5s; }
 .td-i-m { transition-duration: inherit; }
}
@media screen and (min-width: 64em) {
 .td-1-l { transition-duration: 120ms; }
 .td-2-l { transition-duration: .3s; }
 .td-3-l { transition-duration: .6s; }
 .td-4-l { transition-duration: 1s; }
 .td-5-l { transition-duration: 5s; }
 .td-i-l { transition-duration: inherit; }
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
