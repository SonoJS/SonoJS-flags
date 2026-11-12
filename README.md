# `@sonojs/flags`

SVG country flags for [SonoJS](https://sonojs.com) — built for Phone Input and anywhere you need a country icon.

- Site: [sonojs.com](https://sonojs.com)
- Docs: [sonojs.com/docs](https://sonojs.com/docs)
- Preview: [sonojs.com/tools/flags](https://sonojs.com/tools/flags)
- Repo: [github.com/SonoJS/SonoJS-flags](https://github.com/SonoJS/SonoJS-flags)

## Install

```bash
npm i @sonojs/flags
```

## Usage

### HTML (CDN)

No install needed. Swap the country code — e.g. `us`, `gb-eng`, `eu`.

```html
<img
  src="https://cdn.jsdelivr.net/gh/SonoJS/SonoJS-flags@main/flags/us.svg"
  width="20"
  alt="United States"
/>
```

Also available:

```text
https://cdn.jsdelivr.net/npm/@sonojs/flags/flags/us.svg
https://sonojs.com/tools/flags/flags/us.svg
```

### React

```bash
npm i @sonojs/flags
```

```jsx
import usFlag from "@sonojs/flags/flags/us.svg"

export function Flag() {
  return <img src={usFlag} width={20} height={14} alt="United States" />
}
```

Country list (optional):

```js
import countries from "@sonojs/flags/countries.json"
// [{ code, name, dial }, ...]
```

## License

See `LICENSE` and `NOTICE.md`.
