NAME=agiletools
SRC=$(NAME).tex
OUT=$(NAME).pdf

.PHONY: all build

all: build

build: $(OUT)

$(OUT): $(SRC)
	latexmk -pdfxe -pdfxelatex="xelatex -interaction=nonstopmode" $<

.PHONY: clean

clean:
	latexmk -CA
