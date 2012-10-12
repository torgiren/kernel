all: 01_wprowadzenie_do_vim.tex
	pdflatex --interaction=nonstopmode $^
slides_count:
	echo "Jest `grep "begin{frame" 01_wprowadzenie_do_vim.tex|wc -l` slajdów"
