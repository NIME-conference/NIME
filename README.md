# NIME-PDFs2BibTeX

Problem: How to extract metadata from lots of PDF files from the NIME conference series?

Solution: Some python scripts that extract *keywords* and *abstracts* from all the papers (1000+). 

1. The Python based scripts try to open the pdf files, then read them the text and the meta-data Pdf-destiller. 
2. These data are then stored in an XML-stuctured document. 
3. Convert the data to a bibtex-file.

Good to know: 

* The bibtex files are contained within the nime_archive/nime/bibtex folder. They do all have .bib suffixes, but be aware, there is also another 'proposal.bib' with same suffix. 
* The .pdf files can be found in nime_archive/web/XXXX (where the XXXX are the year in question. From 2001 to 2012). 
* The .pdfs are not found in the git repository (they are too big and hence .gitignore d)

## Credits

Originally developed by Ola Løvholm, research assistant at the University of Oslo, Department of Musicology
