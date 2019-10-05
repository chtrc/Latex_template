SRC = *.tex
OBJ = *.pdf
tmpfiles = *.aux *.log *.toc *.fls *.nav *.out *.snm *.fdb_latexmk *.vrb *.gz

$(OBJ):$(SRC)
	xelatex $(SRC)
	rm -rf $(tmpfiles)

clean:
	rm -rf $(tmpfiles)

clean-all:
	rm -rf *.pdf
	rm -rf $(tmpfiles)

