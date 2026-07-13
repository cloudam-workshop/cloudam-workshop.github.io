# CloudAM 2026 website

Static website for the 15th International Workshop on Cloud and Edge Computing, and Applications Management (CloudAM 2026).

## Local preview

Open `index.html` directly in a browser, or run a local HTTP server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a public GitHub repository, for example `cloudam2026`.
2. Upload all files in this folder to the repository root.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**.
5. Select branch `main`, folder `/ (root)`, and click **Save**.
6. The website should become available at `https://YOUR-USERNAME.github.io/cloudam2026/`.

## Content to confirm before launch

- Workshop-specific submission URL.
- Final workshop deadlines.
- Exact workshop day within 1–4 December 2026.
- Technical Programme Committee.
- Contact email, if a dedicated workshop address is created.
- Publication/indexing wording required by UCC 2026.

## Main files

- `index.html`: website content.
- `assets/css/style.css`: colours, layout, and responsive styles.
- `assets/js/script.js`: mobile menu, scroll effects, and active navigation.
- `assets/img/favicon.svg`: browser icon.
