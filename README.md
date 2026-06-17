# Wedding Invitation Site

GitHub Pages static site for Lakshmi & Supreeth.

## CLI deployment

```bash
git clone https://github.com/supushekar/weddingInvitation.git
cd weddingInvitation

# Replace current files with this package's files:
# index.html
# style.css
# assets/

git add .
git commit -m "Build wedding invitation website"
git push origin main
```

Then open:

```text
https://supushekar.github.io/weddingInvitation/
```

## Add YouTube livestream

In `index.html`, replace:

```html
<a class="button disabled" href="#">Coming Soon</a>
```

with:

```html
<a class="button" href="https://youtube.com/live/YOUR_LINK" target="_blank">Watch Live</a>
```

Then run:

```bash
git add index.html
git commit -m "Add livestream link"
git push origin main
```
