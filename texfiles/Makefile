#Makefile for creation and cleaning of the JET presentation 



pdf:
	pdflatex JET_2013.12.06.tex


view-pdf: pdf
	evince JET_2013.12.06.pdf &
clean:
	mv JET_2013.12.06.tex save
	rm -f JET_2013.12.06.*
	rm -f *.log
	mv save JET_2013.12.06.tex

