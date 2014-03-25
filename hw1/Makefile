PROJECT  = hw1
PDFLATEX = pdflatex

all: $(PROJECT).pdf

$(PROJECT).pdf: ex1.tex firstpage.tex hw.tex hwnotitle.tex
	$(PDFLATEX) hw.tex
	$(PDFLATEX) hw.tex

clean:
	rm -f hw.{aux,log}
