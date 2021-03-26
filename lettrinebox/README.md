# Lettrinebox

Lettrinebox creates a box typeset in [EB Garamond](http://www.georgduffner.at/ebgaramond/index.html), with several of the historical font variants activated.
It mostly acts as a wrapper around the [coloredlettrine](https://github.com/raphink/coloredlettrine) package, which creates a decorated dropped initial in two colours of your choosing.
At the moment, there exist only decorated initials for *A*, *G* anf *T*, so you might need to apply some Oulipian constraints to your writing.

The contents of `EBGaramond-0.016` are developed by Georg Duffner and licensed under the [SIL Open Fonts License](https://scripts.sil.org/cms/scripts/page.php?site_id=nrsi&id=OFL).
The file `coloredlettrine.sty` was compiled using the code in Raphaël Pinson's package repository and is licensed under the [LaTeX Project Public License](http://www.latex-project.org/lppl.txt).

To use lettrinebox, add the files in this folder to your working directory.
Import `lettrinebox` and use the command `\lettrinebox{width}{title goes here}{actual text goes here}`.

## Example

![Screenshot of the output of the code below](https://github.com/verenablaschke/tex-packages/blob/main/lettrinebox/lettrinebox-demo-wide.png)

```
\documentclass{article}
\usepackage{lettrinebox}
\begin{document}
\lettrinebox{8cm}{lettrinebox dot sty}{Generates a box typeset in \textit{EB~Garamond},
with several of the historical font variants activated.
It mostly acts as a wrapper around the \textit{coloredlettrine} package,
which creates a decorated dropped initial in two colours of your choosing.
At the moment, it only includes decorated initials for \textit{A}, \textit{G} and \textit{T},
so prepare yourself for Oulipian constraints in your writing.
Enjoy!}
\end{document}
```
