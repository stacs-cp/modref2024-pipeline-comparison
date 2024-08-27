# Ruth's Awesome LaTeX MakeFile



all : $(DOC).tex
	pdflatex $(DOC).tex
	pdflatex $(DOC).tex
	pdflatex $(DOC).tex
	rm -f *.toc *.aux *.log *.out *.nav *.snm *.vrb
	
open : $(DOC).tex
	open $(DOC).pdf

clean :
	rm -f *.toc *.aux *.log *.out *.pdf *.nav *.snm *.vrb

# won't remove the pdf
finish :
	rm -f *.toc *.aux *.log *.out *.nav *.snm *.vrb

help :
	@echo "make DOC=<Filename without .tex>"
	@echo "Recipes are"
	@echo "  all DOC=<Filename without .tex>"
	@echo "  notes DOC=<Filename without .tex>"
	@echo "  slides DOC=<Filename without .tex>"
	@echo "  open DOC=<Filename without .tex>"
	@echo "  clean (which removes the pdf as well)"
	@echo "  finish"
	