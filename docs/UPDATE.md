# Update Guide

Keep this GitHub profile polished by updating the following files when your technology, projects, or contact details change:

- `README.md` — main profile layout, featured projects, and links.
- `assets/hero.svg` — terminal hero banner with animated text.
- `docs/CUSTOMIZE.md` — instructions for editing the repository content.

## Workflow

```bash
git pull origin main
# update files
# preview README in Markdown

git add README.md assets/*.svg docs/CUSTOMIZE.md docs/UPDATE.md .github/README.md
git commit -m "Update GitHub profile assets and documentation"
git push origin main
```

## Notes

- Use `README.md` preview in VS Code or GitHub to verify asset rendering.
- Relative SVG paths are used so local assets render correctly in the profile.
- Keep copy concise and consistent with the premium terminal theme.
