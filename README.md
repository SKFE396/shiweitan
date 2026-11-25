# Shiwei Tan — Academic Homepage

A build-free academic personal homepage made with plain HTML and CSS. It works by opening `index.html` directly and is ready for GitHub Pages.

## Preview locally

Open `index.html` in a browser. No installation or build command is needed.

For a local HTTP preview, run this command from the site folder:

```bash
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy with GitHub Pages

1. Keep `index.html`, `style.css`, and `avatar.jpg` at the repository root.
2. On GitHub, open **Settings → Pages** for this repository.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select `main` and `/ (root)`, then save.
5. Find the published URL in **Settings → Pages** after the deployment finishes.

## Add the missing profile links

The supplied CV source does not include Google Scholar, GitHub, or a public CV PDF URL. To add them:

1. Put a privacy-reviewed CV PDF at `cv.pdf` in this folder.
2. In `index.html`, find the `profile-links` list.
3. Add an item for each link you want to publish.

```html
<li><a href="cv.pdf">CV</a></li>
<li><a href="YOUR_SCHOLAR_URL">Google Scholar</a></li>
<li><a href="YOUR_GITHUB_URL">GitHub</a></li>
```

Before publishing, confirm that the CV PDF does not contain a phone number, home address, or other information you do not want public.

## Update content

- Page content and metadata: `index.html`
- Colors, typography, spacing, and responsive behavior: `style.css`
- The site uses no external fonts, trackers, scripts, or third-party dependencies.
