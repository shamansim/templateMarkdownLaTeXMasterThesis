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
