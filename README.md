# Remon Alberts Website

Static portfolio site ready for local preview and GitHub Pages deployment.

## Local preview

From this folder:

```bash
python3 -m http.server 4173
```

Then open `http://127.0.0.1:4173/`.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Push this folder to the repository's `main` branch.
3. In GitHub, open `Settings` -> `Pages`.
4. Set `Source` to `Deploy from a branch`.
5. Choose branch `main` and folder `/ (root)`.
6. Save and wait for the site to publish.

## Notes

- `.nojekyll` is included so GitHub Pages serves the site as plain static files.
- Most images are marked `loading="lazy"` to avoid loading the full gallery on the first visit.
