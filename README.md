# papers-polite-nool

About
=====
Paper about Polite for: http://2016.splashcon.org/track/nool2016

Installation
============

Some of the required bibliography files are in another git repo. To get them run: 

    ./get-biblio.sh

The `minted` package is used for syntax highlighting. To use it you need to run: 

    easy_install Pygments
    
You must compile your document with the `-shell-escape option`: 

    pdflatex -shell-escape paper.tex 

