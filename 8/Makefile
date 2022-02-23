report.pdf: report.tex
	latexmk -pdf

report.tex: report.md
	pandoc  report.md -o report.tex --from markdown --template avans
