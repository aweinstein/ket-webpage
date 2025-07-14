# Personal Web Page
Based on [Hugo Academic CV Theme](https://github.com/HugoBlox/theme-academic-cv).

## Useful info:
- [Official demo of the theme](https://academic-demo.netlify.app/).
- [Examples](https://hugoblox.com/creators/).
- [Documentation](https://docs.hugoblox.com/).
- Automatically import your publications from BibTeX: [Hugo Academic CLI](https://github.com/GetRD/academic-file-converter).

## What to edit
- Personal info: `content/authors/admin/_index.md`.
- Global setup: `config/_default/hugo.yaml`.
- Global setup: `config/_default/params.yaml`.
- Top menu: `config/_default/menus.yaml`.
- Sections of the landing page: `content/_index.md`.

### Import publications
- Use [academic Python script](https://pypi.org/project/academic/) to import BibTex into `content/publications`.
- `academic import kta.bib content/publication/ --compact`

## TODO
- Enable menus: Talks, News, Experience, Projects, Teaching

## GitHub Repo Creation
- Create the repo in GitHub.
- `git clone https://github.com/HugoBlox/theme-academic-cv.git ket-webpage`
- `cd ket-webpage`
- `git remote rename origin upstream`
- `git remote add origin https://github.com/aweinstein/ket-webpage.git`
- `git remote -v`
- `git push -u origin main`


