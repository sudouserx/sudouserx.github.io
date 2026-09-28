# Ebrahim Aliyou Wudu

Static academic homepage for [GitHub Pages](https://pages.github.com/). No build step.

## Local preview

Open `index.html` in a browser, or from this directory:

```bash
python3 -m http.server 8080
```

Then visit `http://localhost:8080`.

## Edit content

- Page copy and section order: [`index.html`](index.html)
- Typography and layout: [`css/styles.css`](css/styles.css)
- Headshot: [`assets/profile.jpg`](assets/profile.jpg)
- Downloadable CV: [`assets/Ebrahim_Aliyou_Wudu_CV.pdf`](assets/Ebrahim_Aliyou_Wudu_CV.pdf?v=20260928)

Paper, code, Devpost, and project links are taken from the resume. Hosted PDFs currently live on Google Drive.

## Deploy on GitHub Pages

1. Create a GitHub repository. For a root user site, name it `sudouserx.github.io`. Otherwise any name works and the URL will be `https://sudouserx.github.io/<repo>`.
2. Push this directory to the `main` branch.
3. In the repository: **Settings → Pages → Build and deployment**.
4. Set **Source** to **Deploy from a branch**, branch `main`, folder `/ (root)`.
5. After a minute or two the site is live at the URL GitHub shows on that page.

No GitHub Actions workflow is required.
