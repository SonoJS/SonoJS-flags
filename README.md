# `@sonojs/flags`

SVG country flags for [SonoJS](https://sonojs.com) — built for Phone Input and anywhere you need a country icon.

- Site: [sonojs.com](https://sonojs.com)
- Preview: [sonojs.github.io/SonoJS-flags](https://sonojs.github.io/SonoJS-flags)
- Repo: [github.com/SonoJS/SonoJS-flags](https://github.com/SonoJS/SonoJS-flags)

## Install

```bash
npm i @sonojs/flags
```

## Usage

In HTML, use a jsDelivr CDN URL (no install needed). Swap the country code — e.g. `us`, `ir`, `gb-eng`, `eu`.

### npm

```html
<img
  src="https://cdn.jsdelivr.net/npm/@sonojs/flags/flags/ir.svg"
  width="20"
  alt="Iran"
/>
```

Pinned version:

```html
<img
  src="https://cdn.jsdelivr.net/npm/@sonojs/flags@1.0.0/flags/us.svg"
  width="20"
  alt="US"
/>
```

### GitHub

```html
<img
  src="https://cdn.jsdelivr.net/gh/SonoJS/SonoJS-flags@main/flags/ir.svg"
  width="20"
  alt="Iran"
/>
```

Both point to the same SVG files.

### Bundler (optional)

```js
import flag from "@sonojs/flags/flags/ir.svg"
import countries from "@sonojs/flags/countries.json"
```

## Preview

From this project folder:

```bash
npx serve .
```

Open the URL the terminal prints, or open `index.html` directly.

## License

See `LICENSE` and `NOTICE.md`.
