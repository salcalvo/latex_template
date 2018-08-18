# latex_template
Template directory for creating LaTeX documents

The top-level directory here contains some relevant files, and rest of the files/folders support these:

 - the_paper.tex contains the document content to be compiled
 - build_the_paper.sh is the makefile
 - paper.bib is the biblatex bibliography file

To compile the_paper.tex into a PDF and open it, navigate to the latex_template directory in your shell and run:

```
sh build_the_paper.sh
```