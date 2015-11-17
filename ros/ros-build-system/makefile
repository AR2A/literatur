all: arra-ros-build-system.tex
	pdflatex arra-ros-build-system.tex
	bibtex arra-ros-build-system
	pdflatex arra-ros-build-system.tex
	pdflatex arra-ros-build-system.tex
	
clean:
	rm -f *.log *.toc *.aux *.nav *.out *.snm *.bbl *.blg *.synctex.gz
	
cleanall:
	rm -f *.log *.toc *.aux *.nav *.out *.snm *.bbl *.blg *.synctex.gz arra-ros-build-system.pdf
