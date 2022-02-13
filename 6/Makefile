report.pdf: report.tex
	latexmk -C; rm -f report.bbl; latexmk -pdf

report.tex: report.md report.bib
	pandoc --bibliography=report.bib --natbib report.md -o report.tex --from markdown --template avans
