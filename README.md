# vincefung.art

Portfolio site for Vince Fung — Art Director & Character Artist.

Hosted on GitHub Pages, pointed at `vincefung.art` via Squarespace DNS CNAME.

## Deploy

1. Push this repo to GitHub as a public repo named `vincefung.github.io` (or any repo with GitHub Pages enabled)
2. In repo Settings → Pages → Source: Deploy from branch `main`, folder `/` (root)
3. In Squarespace DNS: add a CNAME record pointing `vincefung.art` → `<your-github-username>.github.io`
4. GitHub Pages will automatically provision HTTPS via Let's Encrypt

## Structure

```
index.html      ← main portfolio page
img/            ← all artwork (PNG)
CNAME           ← custom domain config for GitHub Pages
.nojekyll       ← disables Jekyll processing
```
