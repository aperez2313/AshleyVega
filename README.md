# Ashley A. Vega · Portfolio website samples (Option 3)

Two static website directions for Ashley A. Vega's marketing portfolio, both built on the same brand guideline.

| Page | File | Style |
|---|---|---|
| Landing page (pick a sample) | `index.html` | |
| Sample 1 · Home | `sample-1/index.html` | Editorial layout, Navy + Olive (Palette B) |
| Sample 1 · About | `sample-1/about.html` | Editorial layout, Navy + Olive (Palette B) |
| Sample 2 · Home | `sample-2/index.html` | Bold two-tone layout, Navy + Wine (Palette A) |

Plain HTML and inline CSS. No build step and no dependencies apart from Google Fonts (Noto Serif and Noto Sans).

## Put it on GitHub Pages

1. Merge the site into `main` (or pick the branch that holds it in step 2).
2. On GitHub, go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
3. After a minute the site is live at `https://aperez2313.github.io/AshleyVega/`.

To open it locally, double-click `index.html`.

## Before going live

Search the files for `[PLACEHOLDER` to find everything that still needs real content:

- testimonials (Sample 1 Home)
- LinkedIn and Instagram links (all footers)
- Instagram handle (Sample 2)
- resume PDF link (Sample 2)
- a healthcare partner and the contact-form reply time (Sample 1 About)

Links marked `href="#"` point to pages that aren't built yet (Work, Results, Resume, Contact).

The email and contact forms are visual only. To make them send, point them at a form service such as Formspree or Netlify Forms.

The project images are cropped from the PDF portfolio deck, so they're screenshot quality. Replace the files in `assets/images/` with originals, using the same file names, for sharper results.
