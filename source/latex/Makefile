# ./Makefile

# ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ###

ECHOCMD:=/bin/echo -e
LATEX:=lualatex

# ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ###

TARGET:=ua-beamer

# ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ###
# 

default: doc

doc:
	@$(LATEX) $(TARGET).dtx

sty:
	@$(LATEX) $(TARGET).ins

.PHONY: clean

clean:
	@rm -f $(TARGET).aux \
	       $(TARGET).log \
	       $(TARGET).nav \
	       $(TARGET).out \
	       $(TARGET).snm \
	       $(TARGET).toc \
	       $(TARGET).vrb \
	       $(TARGET).pdf \
	       $(TARGET).dvi \
	       $(TARGET).ps  \
	       $(TARGET).bbl \
	       $(TARGET).blg \
	       $(TARGET).thm \
	       $(TARGET).brf \
	       $(TARGET).glo \
	       $(TARGET).idx \
	       $(TARGET).bcf \
	       $(TARGET)-blx.bib \
	       *.sty \
	       missfont.log  \
	       x.log
	@rm -f *~
