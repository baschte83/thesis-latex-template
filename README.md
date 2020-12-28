# thesis-latex-template

This template was created with TeXstudio and using TeXstudio is highly recommended. This template consists of the following files:

- praeamble.tex: Almost all latex configurations
- thesis.tex:
  - Some configurations which can't be separated from \begin{document}
  - Contents and layout for the title page
  - Collects all other separate latex files
- bibliographie.bib
  - Bibliography file with all used citations
  - Created with Zotero
- All other .tex files:
  - All these files represent different chapters of a thesis
  - All these files are collected in thesis.tex to make a complete thesis file of them
- All other files with file endings like .lol, .xml, .synctex.gz, .tdo, etc. ...
  - All these files were created using TeXstudio and are necessary to create the thesis PDF file
- thesis.pdf:
  - PDF file of the whole thesis

To be able to use this template with TeXstudio you must install the following packages first (using "$ sudo apt install [package-name]"):

- texlive
- texlive-lang-german
- texlive-latex-extra
- lmodern
