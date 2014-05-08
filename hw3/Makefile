PROJECT  = hw3
PDFLATEX = pdflatex

all: $(PROJECT).pdf

$(PROJECT).pdf: ex3.tex firstpage.tex hw.tex
	$(PDFLATEX) hw.tex
	$(PDFLATEX) hw.tex

notitle: ex3.tex firstpage.tex hwnotitle.tex
	$(PDFLATEX) hwnotitle.tex
	$(PDFLATEX) hwnotitle.tex

clean:
	rm -f hw.{aux,log}
