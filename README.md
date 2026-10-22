# AGL Tutorial @ ADMA 2026 homepage

Static site served with GitHub Pages: `index.html`, `images/`, `files/`.

## Publish
1. Create an empty public repo on GitHub, e.g. `agl-tutorial` under `leo-q-316`.
2. In this folder:
   git remote add origin https://github.com/leo-q-316/agl-tutorial.git
   git push -u origin main
3. Repo → Settings → Pages → Source: "Deploy from a branch", Branch: `main` / `(root)`.
4. The site appears at https://leo-q-316.github.io/agl-tutorial/

## Add materials later
- Put PDFs in `files/` (e.g. `files/AGL_Tutorial_Slides.pdf`).
- In `index.html`, set each button's `href`, remove `class="soon"` and the `<small>` label;
  replace the "Coming soon" tag in the Materials section with a link.
- Photos: `images/jianxin_li.jpg`, `images/liang_qu.jpg` (see comment in Presenters).
