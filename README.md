# css-filter-contrast

Functional CSS for filter-contrast

## Filesize

| File | Size |
|------|------|
| `dist/filter-contrast.css` | 1229 bytes |
| `dist/filter-contrast.min.css` | 891 bytes (190 Gzipped) |

## Install

```sh
npm install css-filter-contrast
```

## Usage

### Import

```css
@import "css-filter-contrast";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-filter-contrast/dist/filter-contrast.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-filter-contrast/dist/filter-contrast.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.contrast0` | `filter: contrast(0);` |
| `.contrast1` | `filter: contrast(50%);` |
| `.contrast2` | `filter: contrast(75%);` |
| `.contrast3` | `filter: contrast();` |
| `.contrast4` | `filter: contrast(150%);` |
| `.contrast5` | `filter: contrast(200%);` |
| `.contrast0-s` | `filter: contrast(0);` |
| `.contrast1-s` | `filter: contrast(50%);` |
| `.contrast2-s` | `filter: contrast(75%);` |
| `.contrast3-s` | `filter: contrast();` |
| `.contrast4-s` | `filter: contrast(150%);` |
| `.contrast5-s` | `filter: contrast(200%);` |
| `.contrast0-m` | `filter: contrast(0);` |
| `.contrast1-m` | `filter: contrast(50%);` |
| `.contrast2-m` | `filter: contrast(75%);` |
| `.contrast3-m` | `filter: contrast();` |
| `.contrast4-m` | `filter: contrast(150%);` |
| `.contrast5-m` | `filter: contrast(200%);` |
| `.contrast0-l` | `filter: contrast(0);` |
| `.contrast1-l` | `filter: contrast(50%);` |
| `.contrast2-l` | `filter: contrast(75%);` |
| `.contrast3-l` | `filter: contrast();` |
| `.contrast4-l` | `filter: contrast(150%);` |
| `.contrast5-l` | `filter: contrast(200%);` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.contrast0-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/filter-contrast.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/filter-contrast.css` — formatted
- `dist/filter-contrast.min.css` — minified

## License

MIT
