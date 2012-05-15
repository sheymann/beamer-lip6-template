Free and open-source template for **beamer**, which is a LaTeX package for typesetting presentation slides. The theme is designed for use at Université Pierre et Marie Curie (UPMC), [LIP6](http://www.lip6.fr/), and is derived from the amazing [Frederiksberg](http://matdat.life.ku.dk/LaTeX/Frederiksberg/) theme. If you're not from this university, you must change the color scheme and logos.

This template is distributed under the [MIT License](https://github.com/sheymann/beamer-lip6-template/blob/master/LICENSE.txt).

###Sample

Download the sample PDF [here](https://github.com/sheymann/beamer-lip6-template/blob/master/beamer.pdf?raw=true).

###Usage

Edit the main.tex file with your own content.

###Requirements

* install the [Frederiksberg](http://matdat.life.ku.dk/LaTeX/Frederiksberg/) theme v2.2 or later
* compile with pdflatex

###Additional features

Once the content is ready, comment the line
```latex
\documentclass{beamer}
```
and compile 
```
beamer.tex ; handout.tex ; print.tex
```
to generate the handout file and a printable version having 4 slides per page.

###Want to contribute?
The `TODO.txt` file at the root of the project contains different ideas that would improve *beamer-lip6-template*. You can also fill an [issue ticket](https://github.com/sheymann/beamer-lip6-template/issues) if you find a bug or want to request a new feature.