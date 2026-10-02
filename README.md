# allendevaraj.github.io

Personal site. One static page (`index.html`), tabs switched by a few lines of JS, no build step.

```
index.html                 the page
CV                         header link goes to Google Drive (no local copy)
pdf/                       IROS 2026 workshop poster
video/lean_reach.mp4       H1-2 braced-reach clip on the home tab
img/                       photos and thumbnails
```

## Publish

1. Create a public repo named exactly `AllenDevaraj.github.io`.
2. Put these files at the repo root and push to `main`.
3. Settings → Pages → Deploy from a branch → `main` / `(root)`.

Live within a couple of minutes at https://allendevaraj.github.io.

## Editing

Each tab is a `<section class="panel" id="...">`. Add a project by copying an `<article class="entry">` block; add a paper by copying a `<div class="pub">` block. Swap any image in `img/` for a better original under the same filename.
