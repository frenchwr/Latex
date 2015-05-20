# Vanderbilt PhD Dissertation LaTeX Source Files

These are LaTeX source and style files for my PhD Dissertation, which can be found at this page: http://etd.library.vanderbilt.edu/available/etd-03212013-122215/unrestricted/French.pdf

I have uploaded the final compiled PDF of my dissertation, as well as the native LaTeX files used to generate this file. Note that these files alone will not regenerate the PDF document; I include them here for reference. To compile the PDF you would also need the appropriate figure images and the .bib files; .bib files define the references and can be incorporated into your document using BibTex?. Individual .bib files for specific papers can be downloaded from Web of Science or journal websites.

If you are beginning your dissertation document from scratch, start by downloading the thesis.tex and .sty files, then delete all the figure references and \cite commands in the thesis.tex document. The .tex file contains all text of the body of the PDF, sets up the document environment, loads the figures, links to the required packages, etc. You can also split your .tex files up into multiple documents if desired (eg, separate documents for each chapter). The .sty files are LaTeX style files that define some of the important formatting for the document.

== Acknowledgements ==

Note that I did not generate any of the LaTeX files from scratch. I started with the files from this page, and made some minor modifications: https://github.com/hootener/LaTeX-Vanderbilt-Dissertation-Format