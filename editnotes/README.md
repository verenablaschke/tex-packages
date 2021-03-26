# Editnotes

The `editnotes` package allows you to highlight sections of your text that you want to pay special attention to when editing it later.
It currently supports three types of editing notes: `\todo`, `\rephrase` and `\repetition`.
If you would not like the highlighted text to be prepended by a label, you can use the asterisk versions of the commands.
To quickly check how many notes there are left in your document, `\editnotesummary` provides you with an overview.

## Example

![Screenshot of the output of the code below](https://github.com/verenablaschke/tex-packages/blob/main/editnotes/editnotes-demo-wide.png)

```
\documentclass{article}
\usepackage{editnotes}
\begin{document}
\todo{Add an introduction here} lorem ipsum.
\rephrase{Express this differently}.
Test test.
This note doesn't come with a label: \todo*{add more text here}.
Neither does \rephrase*{this one}.
I just used the word \repetition{test} again.
The command \texttt{\textbackslash{}editnotesummary} produces a summary of how many editing notes there are left in your text:
\editnotesummary
\end{document}
```
