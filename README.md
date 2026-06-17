# Lakshmi & Supreeth Wedding Site

Static GitHub Pages website for the wedding livestream.

## Files

- `index.html` - website content
- `style.css` - design and layout
- `assets/design-reference.png` - uploaded reference image

## How to publish on GitHub Pages

1. Upload `index.html`, `style.css`, and the `assets` folder to your public GitHub repository.
2. Go to **Settings → Pages**.
3. Choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
4. Save.
5. Wait 1–2 minutes.

Your URL will look like:

`https://YOUR_USERNAME.github.io/REPO_NAME/`

## How to add the YouTube livestream link

In `index.html`, find:

```html
<a class="button disabled" href="#" aria-disabled="true">Coming Soon</a>
```

Replace it with:

```html
<a class="button" href="https://youtube.com/live/YOUR_LINK" target="_blank">Watch Live</a>
```

Commit the change. GitHub Pages will update automatically.
