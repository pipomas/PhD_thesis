TeX file and pdf
================

This repository contains my PhD thesis and all files to reproduce it.

Repository content
------------------

-   `png`: This folder stores a few portable network graphics.

-   `tikzDevice`: .tex code blocks which can be interpreted with the help of the TikZ package. Used to draw visually pleasing figures. All files get sourced from `diss.tex` at some point.

-   `apacite-mod.bst`: A modified apacite.bst file. It [tweaks the reference style for companies](http://tex.stackexchange.com/questions/304217/reference-list-suppressing-dots-after-company-names-apacite).

-   `bibliography.bib`: Text file with references.

-   `diss.pdf`: Pdf file of my PhD thesis

-   `diss.tex`: Tex file of my PhD thesis

### Prerequisites for reproducing `diss.pdf`

-   You need [LaTeX](https://www.latex-project.org) installed on your system.
-   I recommend using [TeXStudio](https://sourceforge.net/projects/texstudio/) as editor, as it comes with an integrated pdf viewer, live inline preview, advanced syntax-highlighting, live checking of references, citations, latex commands, spelling and grammar.
-   Download this repository (**not only `diss.tex`**) by clicking on the green «*Clone or download*» button in the top right corner, and open `diss.tex` from within the downloaded folder. Do not move it out of the downloaded folder, it will not compile correctly.
-   Compile `diss.tex` multiple times.

last updated on September 05, 2016 :tada:
