# R-template_publication
This is a template for drafting a journal article in Rstudio (bookdown or notebook)

Workflow:
0. Create new GitHub repo for your new publication
1. Duplicate this repo: https://docs.github.com/en/repositories/creating-and-managing-repositories/duplicating-a-repository
2. Adjust YALM-header to become an R notebook (output: html_notebook)
3. Add BibTex file from Zotero (bibliography.bib) (export Zotero-library as BibTex)
4. Draft the article using cross-references to figs and references to BibTex file
5. Export and share with co-authors using bookdown ("output: pdf_document2"" or "output: rticles::springer_article")
6. Copy Latex text from "valgaev_publication_draft" to your Latex template provided by the journal

More info: http://landscapeportal.org/blog/2017/09/06/r-markdown-template-for-a-scientific-manuscript/
