# SonoJS Flags

Square ISO2 flag SVGs for SonoJS `PhoneInput` and other UI.

## Layout

```text
flags/{iso2}.svg   # lowercase, e.g. flags/ir.svg
countries.json     # code / name / dial list used by phone-input
```

## Count

245 SVGs — one per entry in `countries.json`.

## Usage (after this repo is on GitHub)

jsDelivr:

```text
https://cdn.jsdelivr.net/gh/<owner>/SonoJS-flags@main/flags/ir.svg
```

GitHub Pages (if enabled):

```text
https://<owner>.github.io/SonoJS-flags/flags/ir.svg
```

In `PhoneInput`, build the URL from the country `code`:

```ts
const src = `${FLAG_CDN_BASE}/${code.toLowerCase()}.svg`
```

## License

- Repository license: see `LICENSE`
- Flag artwork attribution: see `NOTICE.md` (flag-icons MIT)
