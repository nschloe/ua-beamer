# ./Makefile

# ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ###

LATEX:=lualatex

# ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ###

TARGET:=uaBeamerExample

# ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ###
# 

default: main

main:
	@$(LATEX) $(TARGET)

.PHONY: clean

clean:
	@rm -f $(TARGET)-blx.bib \
	       $(TARGET).aux \
	       $(TARGET).log \
	       $(TARGET).out \
	       $(TARGET).pdf \
	       $(TARGET).toc \
	       $(TARGET).snm \
	       $(TARGET).nav \
	       $(TARGET).bbl \
	       $(TARGET).thm \
	       $(TARGET).run.xml \
	       missfont.log \
	       *~
