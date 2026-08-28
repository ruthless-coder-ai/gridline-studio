# Gridline Studio — Monoline Icon Sets

Hand-built monoline icon sets, exported as matched SVG + PNG pairs, plus a static
showcase site.

## Layout

```
icons/          6 categories × 3 concepts, each as .svg and .png
  contract/     signed-document, signing-pen, sealed-document
  education/    graduation-cap, open-book, pencil
  finance/      growth-chart, banknote, coin
  hospital/     building-cross, cross-badge, first-aid-kit
  technology/   cpu-chip, code-window, cloud
  travel/       globe, suitcase, map-pin
site/           index.html — static showcase, no build step
```

## Using the icons

The SVGs are single-colour monoline paths, so they recolour cleanly with `fill`
or `currentColor`. The PNGs have transparent backgrounds and are ready to drop
into slides or docs as-is.

## The site

`site/index.html` is plain static HTML with no build step or dependencies —
open it directly, or serve the folder.

Deployed via Cloudflare. `.wrangler/` is local state and is not tracked.
