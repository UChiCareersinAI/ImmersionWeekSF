# Materials

Files hosted directly in this repo — handouts, datasets, notebooks, templates,
starter code. Anything that isn't a link to an external service (Google Slides,
Overleaf, Colab) lives here.

## Suggested layout

```
materials/
├── day-1/
├── day-2/
└── day-3/
```

## Linking to a file from the schedule

Use a repo-relative path from `README.md`:

```markdown
[Starter notebook](materials/day-1/starter.ipynb)
```

And an absolute URL from `docs/index.html`, since the Pages site is served from
a different path than the repo:

```html
<a href="https://github.com/UChiCareersinAI/ImmersionWeekSF/blob/main/materials/day-1/starter.ipynb">Starter notebook</a>
```

## Notes

- Keep filenames lowercase with hyphens — no spaces. They become URLs.
- GitHub renders `.ipynb`, `.md`, `.csv`, and `.pdf` in the browser, so students
  can preview without downloading.
- Files over 100 MB are rejected by GitHub. Host large datasets elsewhere and
  link to them instead.
