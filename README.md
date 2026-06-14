# choreganize.app

Static GitHub Pages site for Choreganize, a private chore organizer for iPhone and iPad.

## Structure

- `index.html` home page
- `privacy/index.html` privacy policy, served at `/privacy`
- `style.css` shared styles (light and dark, responsive)
- `favicon.svg` app mark
- `404.html` not-found page
- `CNAME` custom domain (`choreganize.app`)
- `.nojekyll` serve files as-is, no Jekyll build

No build step. Files are served directly by GitHub Pages.

## Updating the privacy policy

The page text mirrors `PRIVACY.md` in the Choreganize app repo. When that file
changes, update `privacy/index.html` to match.

## Local preview

Open `index.html` in a browser, or run a static server from this folder:

    python3 -m http.server 8000

Then visit http://localhost:8000
