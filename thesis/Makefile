all: thesis.pdf
thesis.pdf: 
	pdflatex main.tex -o thesis.pdf
	bibtex main 
	pdflatex main.tex -o thesis.pdf

clean:
	mv main.tex _main
	rm -rf main.*
	mv _main main.tex
