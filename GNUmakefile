FONT ?= Candela
FONT_SIZE ?= 9pt
PANDOC_FLAGS ?= -V geometry:margin=0.75in

resume.pdf: resume.md
	pandoc $< -o $@ \
		--pdf-engine=xelatex \
		-V mainfont="$(FONT)" \
		-V fontsize=$(FONT_SIZE) \
		$(PANDOC_FLAGS)

dump-ast: resume.md
	pandoc $< --to=native | less

clean:
	rm -f resume.pdf
