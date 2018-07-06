uml ?= $(wildcard *.uml)
docs: $(uml:.uml=.svg)

%.svg: %.uml
	plantuml -tsvg -nometadata $<

