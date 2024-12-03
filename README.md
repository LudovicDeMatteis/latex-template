# Latex Template

This project provides an example of structure to work with LaTeX documents.

I designed it for personnal use and I don't pretend it will be usefull for anybody. I nonetheless grant permission for anyone to freely use, modify, and distribute this template.

I personnaly use
[TinyTex](https://yihui.org/tinytex/) (a light-weight distribution of [TeX Live](https://www.tug.org/texlive/)),
so this project is organized assuming `latexmk` will be used to build the document.

## Structure

```
├── main.tex
├── references.bib
├── IEEE_template
├── Imports
├── Bib_files
└── README.md
```

## Github Actions

This project integrates github action to allow for easier sharing of the content of the project:

- [Github Action for Latex](https://github.com/marketplace/actions/github-action-for-latex)
- [GH Release](https://github.com/marketplace/actions/gh-release)
- [GitHub Pages action](https://github.com/marketplace/actions/github-pages-action)

### Deploy PDF to specific Branch
This is broken for now
