TEX = pdflatex
SRC = main.tex

all: main.pdf

main.pdf: $(SRC) support/*.tex Entries/*.tex
	$(TEX) $(SRC)
	$(TEX) $(SRC)

clean:
	rm -f main.pdf main.aux main.log main.out main.toc main.nav main.snm

.PHONY: all clean
