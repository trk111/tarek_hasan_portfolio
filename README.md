# Md. Tarek Hasan — Personal Portfolio

Academic and professional portfolio for Md. Tarek Hasan, Software Engineer and Software Engineering Researcher.

## Files

- `index.html` — main portfolio website
- `cv.pdf` — academic CV linked from the Download CV button
- `favicon.svg` — browser tab icon

## Deploy with GitHub Pages

1. Create a new GitHub repository. For a personal site, the repository can be named `YOUR-USERNAME.github.io`.
2. Upload **all files in this folder** to the repository root.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will provide your website address.

### Custom domain

If you own a domain, GitHub Pages can be configured to use it. Add the domain in **Settings → Pages → Custom domain**, then configure the required DNS records at your domain provider.

## Local preview

You can simply double-click `index.html` to preview the site, or run a local server:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Notes

- The portfolio is a static HTML/CSS/JavaScript website, so no PHP/database/server is required.
- The CV download button points to `cv.pdf` in the same folder.
- The profile visual currently uses a stylized `TH` placeholder. Replace it with a professional photo if desired.
