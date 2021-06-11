# booktemplate-sunrise

A style template for typesetting a novel using the memoir class.
To see how it is used, check [`booktemplate-sunrise-demo.tex`](https://github.com/verenablaschke/tex-packages/blob/main/booktemplate-sunrise/booktemplate-sunrise-demo.tex).

## Page size

To use the actual page size (A5) instead of the version with additional trim allowances for printing, uncomment the `\setstocksize/trimmedsize/trims` commands in the beginning of the style file.
To print and bind this yourself, remove the trim margins (as just described), generate the A5-size PDF, and then run the following:

```
\documentclass{scrartcl}
\usepackage{pdfpages}
\begin{document}
\includepdf[pages=-,signature=16,landscape]{book.pdf}
\end{document}
```

(The signature size can be any multiple of 4 as long as the resulting fold doesn't get too thick.)

## Preview

![Screenshot of most of the pages in booktemplate-sunrise-demo.pdf](https://github.com/verenablaschke/tex-packages/blob/main/booktemplate-sunrise/booktemplate-sunrise-demo.png)
