R = readme

readme: $(R).pdf

all : readme

$(R).pdf: *.tex
	pdflatex $(R)
	pdflatex $(R)

clean:
	rm -f *.aux $(R).log $(R).out $(R).pdf
