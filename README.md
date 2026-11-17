# DynaHOM project page

A lightweight, anonymous research project website for GitHub Pages. The layout follows the academic presentation style of HandMimicX, with an independent implementation and DynaHOM content.

## Preview

Run from this directory:

```bash
python3 -m http.server 8000
```

Open http://localhost:8000.

## Edit

- `index.html`: project title, summary, sections, and embedded styles.
- `materials/`: project images and future demonstration videos.
- Paper and code links are omitted until resources are available.
- The title wording and abstract body follow the latest Overleaf cloud paper (`main.tex` and `sec/0_abstract.tex`). The page heading omits the colon after DynaHOM, and its abstract omits the paper's final project-page link. No author line is displayed.
- Current paper figures: `materials/pipeline_v2.jpg` (framework overview exported from the compiled Overleaf paper, including native text corrections), `materials/real_robot.jpg` (six real-world tasks), and `materials/set_up.jpg` (hardware setup). Each figure opens at full resolution when clicked.

For a video, add its file under `materials/` and replace the demonstration notice with:

```html
<video controls muted loop playsinline preload="metadata" style="width:100%;border-radius:8px">
  <source src="materials/demo.mp4" type="video/mp4">
</video>
```

## GitHub Pages

Enable **Settings → Pages → Deploy from a branch → main → / (root)**. The repository contains `.nojekyll` and requires no build or dependencies.

The repository is `LiuYufei-Robotics/dynahom.github.io`. Its project site is https://liuyufei-robotics.github.io/dynahom.github.io/.

## Anonymous review

All assets use relative URLs and the page has no external fonts, scripts, analytics, or author links. Check images and any added media for identifying content before sharing. To mirror the page through Anonymous GitHub, select this repository and enable **GitHub Pages** in the display settings. Use the generated website URL for reviewers.
