AUXFILES=thesis.aux thesis.log thesis.lof thesis.lot thesis.toc thesis.dvi

all:
	@latex thesis.tex > /dev/null
	@dvipdf thesis.dvi
	@rm -f $(AUXFILES)

clean:
	@rm -f $(AUXFILES) thesis.pdf


