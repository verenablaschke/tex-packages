A (growing) collection of LaTeX packages, some useful, some less so.

<table>
<tr>
  <td colspan="2"><a href="https://github.com/verenablaschke/tex-packages/tree/main/editnotes">editnotes</a>
</td>
</tr>
<tr>
<td>
<pre>
<img src="https://github.com/verenablaschke/tex-packages/blob/main/editnotes/editnotes-demo-slim.png"/>
</pre>
</td>
<td>
<pre>
\documentclass{article}
\usepackage{editnotes}
\begin{document}
\todo{Add an introduction here} lorem ipsum.
\rephrase{Express this differently}.
Test test.
This note doesn't come with a label:
\todo*{add more text here}.
Neither does \rephrase*{this one}.
I just used the word \repetition{test} again.
The command \texttt{\textbackslash{}editnotesummary}
produces a summary of how many editing notes
there are left in your text:
\editnotesummary
\end{document}
</pre>
</td>
</tr>

<tr>
  <td colspan="2"><a href="https://github.com/verenablaschke/tex-packages/tree/main/lettrinebox">lettrinebox</a>
</td>
<tr>
<td>
<pre>
<img src="https://github.com/verenablaschke/tex-packages/blob/main/lettrinebox/lettrinebox-demo-slim.png"/>
</pre>
</td>
<td>
<pre>
\documentclass{article}
\usepackage{lettrinebox}
\begin{document}
\lettrinebox{8cm}{lettrinebox dot sty}{Generates
a box typeset in \textit{EB~Garamond}, with several
of the historical font variants activated.
It mostly acts as a wrapper around the
\textit{coloredlettrine} package, which creates a
decorated dropped initial in two colours of your choosing.
At the moment, it only includes decorated initials
for \textit{A}, \textit{G} and \textit{T}, so prepare
yourself for Oulipian constraints in your writing.
Enjoy!}
\end{document}
</pre>
</td>
</tr>

</table>
