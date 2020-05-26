INPUT=slides.md
OUTPUT=slides.pdf

all: build

build:
	pandoc $(INPUT) -f markdown -t beamer -o $(OUTPUT)

clean:
	@echo "Cleaning up..."
	rm -f $(OUTPUT)

.PHONY: all build clean
