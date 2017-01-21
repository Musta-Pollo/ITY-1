file=proj3

pdf:
	latex ${file}.tex
	latex ${file}.tex
	dvips ${file}.dvi
	ps2pdf -sPAPERSIZE=a4 ${file}.ps

clean:
	rm ${file}.dvi
	rm ${file}.ps
	rm ${file}.pdf
