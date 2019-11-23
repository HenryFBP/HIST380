all: pdf clean

pdf:
	pdflatex --shell-escape part-3-hpost.tex
	pdflatex --shell-escape part-3-hpost.tex

clean:
	rm -f *.aux *.log *.synctex.gz tmp.markdown *.lua *.out
	rm -rf _markdown*/
