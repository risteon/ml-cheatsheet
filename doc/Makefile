SHEETS := $(patsubst %.md,%.md.sheets.pdf,$(wildcard *.md))
WEB := $(patsubst %.md,%.md.sheets.html,$(wildcard *.md))

all : $(SHEETS) $(WEB)

sheets : $(SHEETS)

web : $(WEB)

%.md.sheets.pdf : %.md
	pandoc $^ --from markdown --template eisvogel --listings -o $@ 

%.md.sheets.html : %.md
	pandoc $^ --from markdown --mathjax --listings -o $@ 

clean : 
	rm -f $(SHEETS)
	rm -f $(WEB)
