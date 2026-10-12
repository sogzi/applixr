# Applixr

Landing page for [Applixr](https://applixr.com), the software development company behind
[Naija Games](https://naijagames.applixr.com) and [Gbas Gbos](https://gbas-gbos.applixr.com).

It is a static site with no build step: `index.html`, `styles.css` and `assets/`.

## Run locally

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Deploy

Upload the repository contents to any static host (GitHub Pages, Netlify, Vercel, Cloudflare Pages).
For GitHub Pages, enable Pages on the default branch with the root folder as the source.

## Editing content

- Products live in the `#products` section of `index.html`. Copy an `<article class="row">` block to add one.
- The contact email is set in the `#contact` section.
- Colors and fonts are tokens at the top of `styles.css`.
