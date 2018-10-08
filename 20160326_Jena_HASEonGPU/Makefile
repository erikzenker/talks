MAIN_DOCUMENT?=talk
TEXER=htlatex
TEXER=pdflatex

all: outline talk notes

talk: *.tex
	$(TEXER) $(MAIN_DOCUMENT).tex
	$(TEXER) $(MAIN_DOCUMENT).tex

outline: outline.tex
	pdflatex outline.tex

notes: notes.tex
	pdflatex notes.tex

clean:
	rm -f *.aux
	rm -f *.toc
	rm -f *.bbl
	rm -f *.blg
	rm -f *.out
	rm -f *.bcf
	rm -f *.log
	rm -f *.run.xml
	rm -f *.pyg
	rm -f *.snm
	rm -f *.nav
	rm -f *.atfi


