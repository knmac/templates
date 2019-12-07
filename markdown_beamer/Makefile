INPUT=md_beamer.md
OUTPUT=md_beamer.pdf

all: build

build:
	pandoc $(INPUT) -t beamer -o $(OUTPUT)

clean:
	@echo "Cleaning up..."
	rm -f $(OUTPUT)

.PHONY: all build clean
