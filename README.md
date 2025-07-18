a LaTeX template for final year project report for general usage in  Universiti Malaya.

- ensure LaTeX is installed. Either:
    - online: register on `www.overleaf.com` and copy these files to a new project.
    - windows: `winget install miktex.miktex strawberryperl.strawberryperl` and launch `MikTeX Console` to update packages.
    - ubuntu: `sudo apt install texlive-basic`.
- run `latexmk` to compile, or `lualatex -pvc` to continuously compile.

Make sure to customize the following:

1. [Date](main.tex#L74) (should be the day of signature in original work declaration),
1. [Title](main.tex#L75) and [TitleMS](main.tex#L76)(malay title),
1. [Author](main.tex#L77),
1. [Matric No](main.tex#L78),
1. [IC No](main.tex#L79),
1. [Degree Name](main.tex#L80),
1. [Faculty](main.tex#L81),
1. [Symbols and Abbreviations](main.tex#L123),
1. [Field of Study](frontmatter/original.tex#L24),
1. [Acknowledgements](frontmatter/acknowledgements.tex),
1. [Abstract](frontmatter/abstract.tex),
1. Images in assets folder [`assets/`](assets/) .
1. Everything in content folder [`content/`](content/) .
