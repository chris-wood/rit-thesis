TAR=tar
GZIP=gzip
LATEX=latex
PDFLATEX=pdflatex
BIBTEX=bibtex

report:
	$(PDFLATEX) Report
	$(BIBTEX) Report
	$(PDFLATEX) Report
	$(PDFLATEX) Report
	chmod 660 *.dvi *.aux *.pdf *.bbl *.blg *.log *.lof *.lot *.toc

thesis:
	$(PDFLATEX) Thesis
	$(BIBTEX) Thesis
	$(PDFLATEX) Thesis
	$(PDFLATEX) Thesis
	chmod 660 *.dvi *.aux *.pdf *.bbl *.blg *.log *.lof *.lot *.toc

zip:
	zip rit-cs-capstone-LaTeX.zip *.sty *.tex *.bib makefile

clean:
	/bin/rm -f *.dvi *.aux *.bbl *.blg *.log *.lof *.lot *.toc
