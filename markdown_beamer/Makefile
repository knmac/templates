INPUT=md_beamer.md
OUTPUT=md_beamer.pdf

all: build

build:
	pandoc $(INPUT) -t beamer -o $(OUTPUT)

clean:
	@echo "Cleaning up..."
	rm $(OUTPUT)

.PHONY: all build clean
