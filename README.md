# Diana Mancía — Link Tree

A simple, single-page Linktree-style personal site built with [Astro](https://astro.build).

## Preview it locally

```bash
cd link-tree-style-site
npm install
npm run dev
```

Then open the URL it prints (usually http://localhost:4321).

To preview a production build instead:

```bash
npm run build
npm run preview
```

## How to edit your details

Everything you'll normally change lives in the config block at the top of
[`src/pages/index.astro`](src/pages/index.astro):

- **Name** — the `name` line
- **Bio** — the `bio` line
- **Photo** — the `photo` line (drop your image into `public/` and point it there)
- **Links** — the `links` array (each has a `label`, `url`, and `icon`)

Available icons: `linkedin`, `x`, `instagram`.

## Swapping the profile photo

Add your image to the `public/` folder (e.g. `public/profile.jpg`) and update
the `photo` line to match (e.g. `"/profile.jpg"`). The circular crop is automatic.
