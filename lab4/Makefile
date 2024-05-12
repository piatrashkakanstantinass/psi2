TEX_FILES := $(shell find -name "*.tex")
DRAWIO_FILES := $(shell find -name "*.drawio")

DEPENDENCIES := $(TEX_FILES) $(DRAWIO_FILES)

lab4.pdf: $(DEPENDENCIES)
	pdflatex -shell-escape lab4.tex
