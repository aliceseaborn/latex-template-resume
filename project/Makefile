# Makefile

# ----------------------------------------* CONFIGURATION
SHELL=/bin/bash
FILENAME=resume


# ----------------------------------------* DEFAULT
all: render clean


# ----------------------------------------* RENDERING
render:
	pdflatex ${FILENAME}.tex
	pdflatex ${FILENAME}.tex


# ----------------------------------------* CLEANING
clean:
	rm -f ${FILENAME}.{log,out,aux}
