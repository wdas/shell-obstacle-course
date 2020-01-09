U = userguide

userguide: $(U).pdf

all : userguide

$(U).pdf: *.tex
	pdflatex $(U)
	pdflatex $(U)

clean:
	rm -f *.aux $(U).log $(U).out $(U).pdf
