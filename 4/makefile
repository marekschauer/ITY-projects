#makefile pro projekt c.4 z predmetu ITY - Typografie a publikovani
#Autor: Petr Jirout - 1BIT, VUT FIT
#		xjirou07@stud.fit.vutbr.cz
#Datum: 4/2012
#Popis: Bibliograficke citace

NAME=proj4

all:
	latex $(NAME).tex
	bibtex $(NAME).aux
	latex $(NAME).tex
	latex $(NAME).tex
	dvips -t a4 $(NAME).dvi
	ps2pdf $(NAME).ps

clean:
	rm -f $(NAME).aux $(NAME).dvi $(NAME).ps $(NAME).bbl $(NAME).blg $(NAME).log
