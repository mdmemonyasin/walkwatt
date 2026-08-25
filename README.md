# WALKWATT — Every Step Creates Energy

Marketing site for WALKWATT kinetic floor tiles, which convert footfall into
stored electricity.

**Live site:** https://mdmemonyasin.github.io/walkwatt/

Innovation idea by Mukul Bhoi. Developed & presented by Mukul Bhoi & Team,
students of Sanskar City International School.

## Structure

- `index.html` — the entire site (single page, no build step, no dependencies)
- `assets/logo.svg` — logo

## Swapping in the real logo

The original design referenced `1000102836.png`, which was not included with the
source document, so `assets/logo.svg` is a stand-in wordmark. To use the real
logo, drop the file in as `assets/logo.svg`, or add it under `assets/` and update
the three `<img src="assets/logo.svg">` references in `index.html`.

## Local preview

```
python3 -m http.server 8000
```

Then open http://localhost:8000

## Deploying

Pushing to `master` publishes automatically via GitHub Pages.
