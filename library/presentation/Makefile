## please modify the following line for naming the end products (PDFs, ZIPs, ...)
PROJECTNAME = "Projekt_Wiki"

# Define directories
INPUT = markdown
OUTPUT := output
MODE = draft # can be draft or final

MAINDOCNAME = Presentation
DATESTAMP = `/bin/date +%Y-%m-%d`
DATESTAMP_AND_PROJECT = ${DATESTAMP}_${PROJECTNAME}
# Define the web browser to use for viewing the HTML
HTMLVIEWER = firefox
PDFVIEWER = evince
TOC=false
CSS='themes/custom.css'

#help
#helpThe main targets of this Makefile are:
#help	help	this help
.PHONY: help
help:
	@sed -n 's/^#help//p' < Makefile

#help	all	create slides for all items in the markdown directoy
.PHONY: all
all: setup slides

setup:
	mkdir -p $(OUTPUT)

#help	draft	create draft slides
draft: MODE=draft
draft: slides

#help	final	create slides with embedded resources
final: MODE=final
final: slides

# Define the embed_resources variable conditionally
ifdef MODE
    ifeq ($(MODE),draft)
        EMBED_RESOURCES = --embed-resources
    else
        EMBED_RESOURCES =
    endif
else
    EMBED_RESOURCES =
endif

ifeq ($(TOC),true)
	TOC_CMD =  --toc=true --toc-depth=1
else
	TOC_CMD = --toc=false
endif

#help	view_html	open the generated HTML slides in the default web browser
.PHONY: view_html
view_html: slides
	$(HTMLVIEWER) "index.html" &
	
slides: setup
	pandoc --data-dir="../pandoc" --from markdown+raw_html-markdown_in_html_blocks-native_divs-native_spans -s -t revealjs --template='custom_title_page' -T 📚 --slide-level=2 $(EMBED_RESOURCES) $(TOC_CMD) --css=$(CSS) --reference-location=section "$(INPUT)/$(MAINDOCNAME).md" -o "index.html"

beamer: setup
	pandoc -s -t beamer "$(INPUT)/$(MAINDOCNAME).md" -o "$(OUTPUT)/$(MAINDOCNAME).pdf"

# --------------------------------------------------------

#help	view	view the PDF-file
.PHONY: view
view: beamer
	${PDFVIEWER} "$(OUTPUT)/$(MAINDOCNAME).pdf" &

# --------------------------------------------------------

#help	clean	clean up temporary files
.PHONY: clean
clean:
	@echo "Cleaning up generated files..."
	
#help	purge	cleaner than clean ;-)
.PHONY: purge
purge: clean
	-rm -r $(OUTPUT)

#help	force	force rebuild next run
.PHONY: force
force:
	touch */*md

