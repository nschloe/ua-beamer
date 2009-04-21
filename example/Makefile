# ./Makefile

# ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ###

ECHOCMD:=/bin/echo -e
PDFLATEX:=pdflatex

# ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ###

TARGET:=uaBeamerExample

# ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ###
# 

default: main

main:
	@$(PDFLATEX) $(TARGET)

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
	       missfont.log  \
	       x.log
	@rm -f *~
