# Brand Fashion Preview

Static preview package built from the uploaded `Reel.fig` / screenshots.

## Files

```txt
index.html
styles.css
assets/
.nojekyll
```

## Local preview

Open `index.html` directly in your browser, or run:

```powershell
python -m http.server 5500
```

Then open:

```txt
http://localhost:5500
```

## GitHub repo suggestion

Suggested new repo name:

```txt
reel-preview
```

Preview URL after GitHub Pages is enabled:

```txt
https://webapp18.github.io/reel-preview/
```

## Push commands

After creating an empty repo on GitHub under `WebApp18` named `reel-preview`, run these from inside this folder:

```powershell
git init
git branch -M main
git remote add origin https://WebApp18@github.com/WebApp18/reel-preview.git
git add .
git commit -m "Add fashion website preview"
git push -u origin main
```

Then enable Pages:

```txt
Repo Settings → Pages → Deploy from a branch → main → /root → Save
```
