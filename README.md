# css-transition-duration

Functional CSS for transition-duration

## Filesize

| File | Size |
|------|------|
| `dist/transition-duration.css` | 1205 bytes |
| `dist/transition-duration.min.css` | 867 bytes (190 Gzipped) |

## Install

```sh
npm install css-transition-duration
```

## Usage

### Import

```css
@import "css-transition-duration";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-transition-duration/dist/transition-duration.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-transition-duration/dist/transition-duration.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.td-1` | `transition-duration: .12s;` |
| `.td-2` | `transition-duration: .3s;` |
| `.td-3` | `transition-duration: .6s;` |
| `.td-4` | `transition-duration: 1s;` |
| `.td-5` | `transition-duration: 5s;` |
| `.td-i` | `transition-duration: inherit;` |
| `.td-1-s` | `transition-duration: .12s;` |
| `.td-2-s` | `transition-duration: .3s;` |
| `.td-3-s` | `transition-duration: .6s;` |
| `.td-4-s` | `transition-duration: 1s;` |
| `.td-5-s` | `transition-duration: 5s;` |
| `.td-i-s` | `transition-duration: inherit;` |
| `.td-1-m` | `transition-duration: .12s;` |
| `.td-2-m` | `transition-duration: .3s;` |
| `.td-3-m` | `transition-duration: .6s;` |
| `.td-4-m` | `transition-duration: 1s;` |
| `.td-5-m` | `transition-duration: 5s;` |
| `.td-i-m` | `transition-duration: inherit;` |
| `.td-1-l` | `transition-duration: .12s;` |
| `.td-2-l` | `transition-duration: .3s;` |
| `.td-3-l` | `transition-duration: .6s;` |
| `.td-4-l` | `transition-duration: 1s;` |
| `.td-5-l` | `transition-duration: 5s;` |
| `.td-i-l` | `transition-duration: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.td-1-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/transition-duration.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/transition-duration.css` — formatted
- `dist/transition-duration.min.css` — minified

## License

MIT
