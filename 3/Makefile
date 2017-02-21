filename=proj3

${filename}.pdf:${filename}.tex
	latex ${filename}.tex
	latex ${filename}.tex
	dvips ${filename}.dvi
	ps2pdf -sPAPERSIZE=a4 ${filename}.ps
