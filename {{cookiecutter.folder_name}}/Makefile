default: slides.pdf

slides.pdf: slides.md header.tex
	pandoc -t beamer -H header.tex --latex-engine=xelatex $< -o $@
