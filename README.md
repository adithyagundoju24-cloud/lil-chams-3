# Lil' Cham Foodies Menu

This is a static HTML and CSS website. It has no build step or package dependencies.

## Preview locally

From the project root, run:

```powershell
python -m http.server 8080
```

Then open <http://127.0.0.1:8080/>.

## Publish with GitHub Pages

1. Create a public repository on GitHub Free.
2. Add the contents of this folder to the repository root, including `index.html`, `menu.css`, `images/`, `fonts/`, and `.nojekyll`.
3. In the repository, open **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, select the `main` branch and `/(root)`, then save.
5. After deployment completes, open the Pages URL shown in the repository settings.

The site uses relative asset paths, so it works from the repository root or a GitHub Pages project subpath.
