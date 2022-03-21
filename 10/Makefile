report.pdf: report.tex poster.bib
	latexmk -pdf report.tex

report.tex:
	pandoc --natbib report.md -o report.tex --from markdown --template avans
