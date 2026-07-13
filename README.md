# Leo Lin — personal website

Simple personal site in the same format as [advaitpatel.com](https://advaitpatel.com/). 

## Local preview

Open `index.html` in a browser

## Publish on GitHub Pages

1. Create a new repo named `LeoLin6.github.io` (for `https://leolin6.github.io`), or any repo and enable Pages from the `main` branch root.
2. Push this folder:

```bash
git init
git add index.html resume.pdf README.md
git commit -m "Add personal website"
git branch -M main
git remote add origin https://github.com/LeoLin6/LeoLin6.github.io.git
git push -u origin main
```

3. In the repo settings → Pages → Source: Deploy from branch → `main` / `/ (root)`.
