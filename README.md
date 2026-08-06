# Hairu Fan Academic Website

Personal academic website published with GitHub Pages.

- Website: https://hairufan.github.io/
- Publications page: https://hairufan.github.io/publications.html
- Publication data: `publications.json`

## Update a publication

1. Open `publications.json` on GitHub.
2. Click the pencil icon (**Edit this file**).
3. To add a publication, copy one complete object inside the `publications` array.
4. Update its `id`, `type`, `status`, `year`, `title`, `authors`, `venue`, `apa`, `url`, `linkLabel`, and `bibtex` fields.
5. Update the top-level `lastUpdated` date using `YYYY-MM-DD`.
6. Commit the change. GitHub Pages will rebuild the public website automatically.

Direct edit link after this feature is merged:

https://github.com/HairuFan/hairufan.github.io/edit/main/publications.json

## Common status values

- `Published`
- `In press`
- `Preprint`

## Common type values

- `Journal Article`
- `Conference Paper`
- `Conference TREO`
- `Preprint`

The publications page automatically provides search, category filters, publication counts, external links, APA copy, and BibTeX copy. Page layout and behavior are kept separate from `publications.json`, so routine publication updates do not require editing HTML.

## Main files

- `index.html`: academic homepage
- `publications.html`: interactive publication archive
- `publications.json`: editable publication records
- `HairuFan_Resume.pdf`: CV/resume PDF
- `JSM2025_Slides.pdf`: presentation slides
