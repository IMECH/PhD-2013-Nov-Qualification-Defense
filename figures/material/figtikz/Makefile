all:
        rm -f simple-flow-chart.pdf
	pdflatex simple-flow-chart.tex
	pdflatex simple-flow-chart.tex

clean:
        find . -name '*.aux' -type f -exec rm -rf {} \;
        find . -name '*.bbl' -type f -exec rm -rf {} \;
        find . -name '*.blg' -type f -exec rm -rf {} \;
        find . -name '*.log' -type f -exec rm -rf {} \;
        find . -name '*.nav' -type f -exec rm -rf {} \;
        find . -name '*.out' -type f -exec rm -rf {} \;
        find . -name '*.snm' -type f -exec rm -rf {} \;
        find . -name '*.toc' -type f -exec rm -rf {} \;
        find . -name '*.vrb' -type f -exec rm -rf {} \;

