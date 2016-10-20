#
# makefile para a compila��o do documento
#
# S�b Jun 23 21:13:37 BRT 2007
#

BASE_NAME = thiago-diss

make:
	latexmk -pdf thiago-diss.tex

clean:
	rm -f $(BASE_NAME)*.ps $(BASE_NAME)*.dvi *.log \
	      *.aux *.blg *.toc *.brf *.ilg *.ind *.fdb_latexmk *.fls *.bbl *.idx \
	      missfont.log $(BASE_NAME)*.bbl $(BASE_NAME)*.pdf $(BASE_NAME)*.out \
		  $(BASE_NAME)*.lof $(BASE_NAME)*.lot $(BASE_NAME)*.gz
