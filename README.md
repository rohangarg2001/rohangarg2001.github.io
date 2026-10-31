# Rohan Garg — personal website

A responsive, static academic website. No Node, Jekyll, dependencies, or build step required.

## Preview locally

From this directory:

```sh
python3 -m http.server 8000
```

Open http://localhost:8000.

## Publish to GitHub Pages

1. Sign in as `rohangarg2001` and create a **public** repository named exactly `rohangarg2001.github.io`. If it already exists, use that repository.
2. Upload the **contents** of this directory into the repository root: `index.html`, `style.css`, `.nojekyll`, and the `assets` directory. Do not upload the enclosing `website` directory.
3. Under **Settings → Pages**, choose **Deploy from a branch**, **main**, and **/ (root)**, then Save.
4. Wait for the Pages deployment to finish. The site will be at https://rohangarg2001.github.io/.

See GitHub's official guide: https://docs.github.com/en/pages/quickstart.

## Update content

Edit `index.html` for text and links, and `style.css` for appearance. Commit changes to `main` to update the live site automatically.

`assets/resume.pdf` is a snapshot of the current resume. After editing `../main.tex`, compile it with `pdflatex` and replace this PDF.

The layout is independently implemented, inspired by the clean academic structure at https://jonasfrey96.github.io/; no template code or third-party photos are copied.
