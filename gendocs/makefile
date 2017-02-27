inputFiles = 
htmlOutput = ../index.html
pdfOutput = ../doc.pdf
htmlOptions = -H style.html --toc -V docheader:"SeaGrant Wiki" --template=default.html5
pdfOptions = --toc --listings --template=default.latex -V title:"SeaGrant Wiki" -V monofont:"beramono" -V geometry:margin=1in -V urlcolor:blue --latex-engine=pdflatex

all: html pdf

html: $(inputFiles)
	pandoc $(htmlOptions) -s -o $(htmlOutput) $(inputFiles)

pdf: $(inputFiles)
	pandoc $(pdfOptions) -s -o $(pdfOutput) $(inputFiles)

clean:
	rm -f $(htmlOutput) $(pdfOutput)