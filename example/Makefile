# ./Makefile

# ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ###

LATEXMK:=latexmk
LATEXMK_OPTIONS:=-pdf

# ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ###

TARGET:=uaBeamerExample

# ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ### ###
# 

default: main

main:
	@$(LATEXMK) $(LATEXMK_OPTIONS) $(TARGET)

.PHONY: clean

clean:
	$(LATEXMK) -C
	@rm -f $(TARGET)-blx.bib \
	       $(TARGET).snm \
	       $(TARGET).nav \
	       $(TARGET).bbl \
	       $(TARGET).thm \
	       $(TARGET).run.xml \
	       missfont.log \
	       *~
