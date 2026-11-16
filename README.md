# DynaMimic project page

A lightweight, anonymous research project website for GitHub Pages. The layout follows the academic presentation style of HandMimicX, with an independent implementation and DynaMimic content.

## Preview

Run from this directory:

```bash
python3 -m http.server 8000
```

Open http://localhost:8000.

## Edit

- `index.html`: project title, summary, sections, and embedded styles.
- `materials/`: project images and future demonstration videos.
- Paper and code are marked as coming soon until public review-ready resources are available.
- The initial summary is adapted from the local DynaHOM draft; update the final paper title and abstract when ready.

For a video, add its file under `materials/` and replace the demonstration notice with:

```html
<video controls muted loop playsinline preload="metadata" style="width:100%;border-radius:8px">
  <source src="materials/demo.mp4" type="video/mp4">
</video>
```

## GitHub Pages

Enable **Settings → Pages → Deploy from a branch → main → / (root)**. The repository contains `.nojekyll` and requires no build or dependencies.

Only a repository named `<owner>.github.io` is served at the account root. A repository named `dynamimic.github.io` under a different account is a project site at `https://<owner>.github.io/dynamimic.github.io/`.

## Anonymous review

All assets use relative URLs and the page has no external fonts, scripts, analytics, or author links. Check images and any added media for identifying content before sharing. To mirror the page through Anonymous GitHub, select this repository and enable **GitHub Pages** in the display settings. Use the generated website URL for reviewers.
