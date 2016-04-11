# templateMarkdownLaTeXMasterThesis
Template to write my master thesis in markdown but included within a LaTeX preformated template (independant titlepage, ending abstract, etc.)

---

There is just one remaining issue, you will have to remove the first page, using a pdf editor. 

For instance `pdftk in.pdf cat 2-end output out1.pdf` should do it.

The table of content or the pagination is not impacted!

How to do
=========

- Just `git clone git@github.com:shamansim/templateMarkdownLaTeXMasterThesis.git`
- Then open RStudio and open `masterThesis.Rmd`
- Push `Knit PDF` button
- Enjoy!
- Don't forget to personalise your `sub/` files

Bibliography
============
- https://support.rstudio.com/hc/en-us/articles/200552056-Using-Sweave-and-knitr
- https://support.rstudio.com/hc/en-us/articles/200532257-Customizing-LaTeX-Options
- https://support.rstudio.com/hc/en-us/articles/200486298
- http://texblog.org/2011/12/01/sweave-subfig-controlling-figure-size-and-placement/
- http://rmarkdown.rstudio.com/pdf_document_format.html
- https://github.com/jgm/pandoc-templates/blob/master/default.latex
- http://stackoverflow.com/questions/17097894/markdown-tag-for-document-title
- https://www.rstudio.com/wp-content/uploads/2015/03/rmarkdown-reference.pdf
- https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet
- http://rmarkdown.rstudio.com/authoring_bibliographies_and_citations.html
