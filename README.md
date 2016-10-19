Preprint
========

[HERE!](preprint.pdf)

About
=====
Paper was presented at the [NOOL (New Object Oriented Languages)](http://2016.splashcon.org/track/nool2016) workshop in 2016. Workshop was collocated with SPLASH. Presents the idea of introducing "sentence case identifiers" in programming languages. 

To try out polite, [download it from Zenodo](https://zenodo.org/record/61578#.WAdi7x8xD0o).

Installation
============

Some of the required bibliography files are in another git repo. To get them run: 

    ./get-biblio.sh

The `minted` package is used for syntax highlighting. To use it you need to run: 

    easy_install Pygments
    
You must compile your document with the `-shell-escape option`: 

    pdflatex -shell-escape paper.tex 

Alternatively, if you use Sublime Text, you can add the following in LaTeXTools.sublime-settings under `builder_settings`:

    "options": ["-shell-escape"]
