pdf:
	pdflatex tp.tex

ignorando-errores:
	pdflatex -interaction=nonstopmode tp.tex

bibliografia:
	pdflatex ejemplo_tp_grupal.tex
	bibtex ejemplo_tp_grupal.aux
	pdflatex ejemplo_tp_grupal.tex
	pdflatex ejemplo_tp_grupal.tex

clean:
	- rm -f *.log *.soc *.toc *.aux *.out  main.idx *.bbl *.bbg *.dvi *.blg *.lof *.nav *.snm *~

