# Nguyen Tran Huy — GitHub Pages CV

A one-page, responsive CV website built with plain HTML and CSS. No framework or build step is required.

## Edit your information

Open `index.html` and replace every placeholder:

- `YOUR_USERNAME`
- `your.email@example.com`
- `DD / MM / YYYY`
- `3.XX`
- Project repository links and final evaluation numbers

To add a portrait, create `assets/profile.jpg`, then replace the commented photo-placeholder block using the instruction inside `index.html`.

For each GPA bar, set `--value` to `GPA / 4 × 100%`. For example, GPA `3.60` becomes `--value:90%`.

## Publish at `https://YOUR_USERNAME.github.io`

1. Create a public GitHub repository named exactly `YOUR_USERNAME.github.io`.
2. Upload `index.html`, `styles.css`, and the optional `assets` folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch **main**, folder **/(root)**, then save.

GitHub will publish the CV at `https://YOUR_USERNAME.github.io` after a short build.

If you prefer a project repository such as `cv`, publish it at `https://YOUR_USERNAME.github.io/cv/` using the same Pages settings.
