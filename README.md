# Lakshmi & Supreeth Wedding Invitation Website

This is a static GitHub Pages website based on the invitation-style screenshot.

## Upload to GitHub

Upload these files to the root of your repository:

- `index.html`
- `style.css`
- `README.md`

No assets folder is required.

## Enable GitHub Pages

Repository → Settings → Pages

Use:

- Source: Deploy from a branch
- Branch: main
- Folder: /root

Your site should be:

`https://supushekar.github.io/weddingInvitation/`

## Add YouTube livestream link

In `index.html`, find:

```html
<a class="watch-button disabled" href="#">Coming Soon</a>
```

Replace with:

```html
<a class="watch-button" href="https://youtube.com/live/YOUR_LINK" target="_blank">Watch Live</a>
```
