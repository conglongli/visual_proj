TARGET=paper
all: pdf

pdf:
	GS_OPTIONS=-dPDFSETTINGS=/prepress rubber --pdf -Wrefs -Wmisc paper

clean:
	rm -f *.aux *.log *.out *.bbl *.blg *~ *.bak $(TARGET).ps $(TARGET).pdf

