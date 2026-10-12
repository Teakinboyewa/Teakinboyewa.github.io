# Temitope Akinboyewa — personal website

A plain HTML/CSS academic website for GitHub Pages. It has no build step and no dependencies.

## Put it online (about 10 minutes)

1. Sign in to GitHub as **Teakinboyewa**.
2. Create a new **public** repository named exactly **`Teakinboyewa.github.io`**. Don't add a README.
3. On the new repo page, click **"uploading an existing file"**. Unzip this folder on your computer, then drag in **everything inside it**: the `.html` files, `assets/`, `files/` and `.nojekyll`. Click **Commit changes**.
   *(Tip: `.nojekyll` is a hidden file. On a Mac, press Cmd+Shift+. in Finder to see it.)*
4. Go to **Settings → Pages**. Under "Build and deployment", choose **Deploy from a branch**, select **main** and **/ (root)**, then click **Save**.
5. After 1–2 minutes your site is live at **https://teakinboyewa.github.io**.

## Things to personalize

| What | Where |
|---|---|
| Your photo | Add a portrait named `profile.jpg` to `assets/img/`. Until then, a "TA" placeholder shows. |
| CV | Replace `files/Akinboyewa_CV.pdf` with your latest PDF, using the same file name. |
| Bio / tagline | `index.html`: the hero paragraph and the "About" section. |
| Courses you TA'd | `teaching.html`: uncomment the "Courses" block and fill it in. |
| New paper / talk / award | Copy an existing `<li>…</li>` in the matching page and edit it. |
| Colors | Top of `assets/css/style.css` (`--brand`, `--gold`, and the rest). |

To edit a file on GitHub, open it and click the pencil icon. Changes go live about a minute after you commit.

## Files

```
index.html          Home: hero, about, education, highlights
research.html       Research themes, open-source tools, media
publications.html   Journal articles, book chapter, under review
awards.html         Fellowships & awards
presentations.html  Talks, posters, sessions chaired
teaching.html       Teaching experience & recognition
links.html          Scholar, ResearchGate, GitHub, CV, projects
assets/css/style.css
assets/img/         put profile.jpg here
files/Akinboyewa_CV.pdf
```
