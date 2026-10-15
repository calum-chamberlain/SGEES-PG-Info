# SGEES PG Info

Files and information common to postgrad students in SGEES at VUW.

Most instructions for use are included as comments in the thesis.tex document.

## Organisation
It is good practice to have each chapter in a separate .tex document and use include statements in the main
thesis.tex file to include them in the thesis (you can then comment out chapters if you find it is taking too long to
compile the document while you work on one chapter).

### Figures
Put figures in the figures directory, you may also want to use sub-directories for each chapter in there. If you do you
will need to give the full path for `\includegraphics` or add an extra `\graphicspath{}` command to thesis.tex.

## Bibliography
Either put references in the refs.bib file, or use some other way (e.g. Overleafs Mendelay plugins) to manage citations.
