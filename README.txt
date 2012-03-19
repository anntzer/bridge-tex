----------------------------------------------------------------
bridge --- Typesetting bridge-related stuff
E-mail: anntzer.lee(at)gmail.com
Released under the LaTeX Project Public License v1.3c or later
See http://www.latex-project.org/lppl.txt
----------------------------------------------------------------

A package for typesetting bridge-related stuff.

See bridge.pdf in the Downloads section for the documentation, with some
examples.

The package is supplied in dtx format.  Running "tex bridge.dtx" will extract
the package.  To extract it and typeset the documentation, use
pdflatex bridge.dtx
makeindex -s gind.ist -o bridge.ind bridge.idx
makeindex -s gglo.ist -o bridge.gls bridge.glo
pdflatex bridge.dtx
