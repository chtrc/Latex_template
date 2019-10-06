SRC = *.tex
OBJ = *.pdf
tmpfiles = *.aux *.log *.toc *.fls *.nav *.out *.snm *.fdb_latexmk *.vrb *.gz

$(OBJ):$(SRC)
	latexmk

clean:
	rm -rf $(tmpfiles)

