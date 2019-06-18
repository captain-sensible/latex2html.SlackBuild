LATEX to HTML convertor
LaTeX is a high-quality typesetting system; it includes features 
designed for the production of technical and scientific
documentation. Latex2html is used for converting Latex files 
to html.

a basic latex document , when opened with say geany will look like this:

\documentclass{article}
\begin{document}
  Hello World!
\end{document}

if you save such a document with a .tex suffix,eg helloworld.tex 
 you have a basic latex document.

To use latex2html to convert this document html form, open a terminal 
and cd to where  helloworld.tex is.

Then its a simple as
$latex2html helloworld.tex 


The purpose for this slackbuild was that it is aimed
at noobs who are folowing along this document 
https://www.slackwiki.com/Writing_A_SlackBuild_Script


 
