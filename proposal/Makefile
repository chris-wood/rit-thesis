all:
	pdflatex arl_proposal.tex
	bibtex arl_proposal
	pdflatex arl_proposal.tex
	pdflatex arl_proposal.tex

clean:
	-rm *.aux *.bbl *.blg *.idx *.log *.bak *~ *.pdf
