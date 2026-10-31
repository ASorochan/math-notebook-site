# Math Notebook website

Static public site for Math Notebook: product overview, privacy policy, support, and terms.

## Local preview

```bash
python3 -m http.server 8080 --directory site
```

Open <http://localhost:8080/>.

## Publishing

This repository deploys `site/` to GitHub Pages on every push to `main`. In the GitHub repository settings, set
**Pages → Build and deployment → Source** to **GitHub Actions**.

Expected public URLs:

- <https://asorochan.github.io/math-notebook-site/>
- <https://asorochan.github.io/math-notebook-site/privacy/>
- <https://asorochan.github.io/math-notebook-site/support/>
- <https://asorochan.github.io/math-notebook-site/terms/>

The application icon and product screenshot are copied from the Math Notebook release assets.
