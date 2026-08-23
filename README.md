# Guanren Zhou — personal website

Source for Guanren Zhou's academic and research website. The site is a small,
dependency-free static page built for GitHub Pages.

## Local preview

From the repository root:

```bash
python -m http.server 8000
```

Then open `http://localhost:8000/`.

## Structure

- `index.html` contains the page content and metadata.
- `assets/css/style.css` preserves the original Jon Barron template styling.
- `assets/images/projects/` contains web-optimized research figures.

The profile photograph is stored at `assets/images/profile.png`.

## Deployment note

The intended root URL is `https://nutlettt.github.io/`, so the GitHub repository
must ultimately be named `Nutlettt.github.io`. The current remote repository,
`Nutlettt/Nutlettt`, is GitHub's special profile repository and would publish as
a project site rather than the account's root site.

After the repository is renamed or recreated, publish from the `main` branch and
the repository root in **Settings → Pages**.

## Credits

The site is a faithful content adaptation of
[Jon Barron's academic website template](https://github.com/jonbarron/jonbarron.github.io):
the original 800px table layout, typography, spacing, colors, profile treatment,
and publication-row structure are retained. Guanren's content and research
figures replace the template content, and no publication is highlighted.
