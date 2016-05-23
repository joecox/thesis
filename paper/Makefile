AUXFILES=thesis.aux thesis.log thesis.lof thesis.lot thesis.toc thesis.dvi thesis.bbl thesis.blg

all:
	@latex thesis.tex > /dev/null
	@bibtex thesis.aux > /dev/null
	@latex thesis.tex > /dev/null
	@latex thesis.tex > /dev/null
	@dvipdf thesis.dvi
	@rm -f $(AUXFILES)

clean:
	@rm -f $(AUXFILES) thesis.pdf


