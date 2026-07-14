# London dwelling-stock change dashboard

A static, self-contained interactive dashboard (built with [marimo](https://marimo.io),
exported to WebAssembly) exploring a statistical model's estimates of annual
dwelling-stock change per London LSOA, 2012-2021.

This repo holds only the exported static site — `index.html` plus its supporting
JS/WASM/font assets. There is no source data, model code, or private information
here; the site itself is entirely self-contained and runs client-side in the
browser once loaded.

**Live site**: enable GitHub Pages on this repo (Settings → Pages → Deploy from a
branch → `main` / `/ (root)`) and it will be served at
`https://<owner>.github.io/<repo>/`.

Generated from a private modelling repository — this repo is a deploy target only,
not where the site's content is developed. To update it, regenerate the export
there and push the new contents here.
