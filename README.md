# haofeiliang.github.io

Personal academic website for Haofei Liang, built with [Zola](https://www.getzola.org/) and the [tabi](https://github.com/welpo/tabi) theme.

## Content

- `content/_index.md`: home page and research summary
- `content/publications/_index.md`: publications
- `content/projects/`: research software and project pages
- `content/cv/_index.md`: CV download page
- `content/blog/`: blog posts
- `static/img/`: profile and site images
- `static/assets/pdf/`: downloadable CV files

The theme is kept separately as the `themes/tabi` Git submodule.

## Local development

This site currently targets Zola 0.22.1.

```powershell
git submodule update --init --recursive
zola check
zola serve
```

Open <http://127.0.0.1:1111/>.

## Updating the CV

Build the PDFs from the separate private CV source directory, then copy the generated files to:

- `static/assets/pdf/main-en.pdf`
- `static/assets/pdf/main-cn.pdf`

`static/assets/pdf/mian-cn.pdf` is retained only for compatibility with the old site URL.
