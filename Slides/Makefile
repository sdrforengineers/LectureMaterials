
LECTURES := L01 L02 L03 L04 L05 L06 L07 L08 L09 L10 L11 L12 L13 L14 L15 L16 L17 L18 L19 L20 L21 L22
LABS := Lab0 Lab1p1 Lab1p2 Lab3p1

lectures: $(LECTURES)

labs: $(LABS)

all: $(LECTURES) $(LABS)

.PHONY: clean
clean:
	rm *.aux *.blg *.out *.bbl *.log *.snm *.toc *.nav *.vrb

clean_pdf:
	rm *.pdf

%: %.tex
	pdflatex --interaction=batchmode $@
