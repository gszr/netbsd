SRC   := netbsd
SHELL := /bin/bash

all: $(SRC).pdf

$(SRC).pdf: $(SRC).tex
	pdflatex $<

clean:
	find -name "$(SRC).*" ! -name "$(SRC).tex" -delete
