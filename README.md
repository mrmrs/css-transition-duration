# CSS TRANSITION DURATION

  Mobile-first classes for css-transition-duration.
  Set the desired css-transition-duration on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
```
npm install --save-dev css-transition-duration
```
or download the css on github and include in your project.

## File Size


## The Code
```
.td-1 { transition-duration: 120ms; }
.td-2 { transition-duration: .3s; }
.td-3 { transition-duration: .6s; }
.td-4 { transition-duration: 1s; }
.td-5 { transition-duration: 5s; }
.td-i { transition-duration: inherit; }

@include break(not-small) {
  .td-1-ns { transition-duration: 120ms; }
  .td-2-ns { transition-duration: .3s; }
  .td-3-ns { transition-duration: .6s; }
  .td-4-ns { transition-duration: 1s; }
  .td-5-ns { transition-duration: 5s; }
  .td-i-ns { transition-duration: inherit; }
}

@include break(medium) {
  .td-1-m { transition-duration: 120ms; }
  .td-2-m { transition-duration: .3s; }
  .td-3-m { transition-duration: .6s; }
  .td-4-m { transition-duration: 1s; }
  .td-5-m { transition-duration: 5s; }
  .td-i-m { transition-duration: inherit; }
}

@include break(large) {
  .td-1-l { transition-duration: 120ms; }
  .td-2-l { transition-duration: .3s; }
  .td-3-l { transition-duration: .6s; }
  .td-4-l { transition-duration: 1s; }
  .td-5-l { transition-duration: 5s; }
  .td-i-l { transition-duration: inherit; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

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

