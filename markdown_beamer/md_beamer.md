---
theme: metropolis
toc: false
slide_level: 2
output: beamer_presentation
classoption: 'aspectratio=169'
header-includes: \metroset{progressbar=frametitle,sectionpage=progressbar}

title: pandoc beamer
subtitle: subtitle
author: Khoi-Nguyen C. Mac
institute: UIUC
date: 12/34/5678
---

# Section 1

## Slide 1
Command to build the output:

```bash
pandoc [markdown_file.md] -t beamer -o [output_file.pdf]
```

## Slide 2
- item 1
- item 2
	- item 3

# Section 2
## Slide 3
### Slide 3.1
$$E=mC^2$$

## Slide 4
| a | b | c |
|---|---|---|
| 0 | 1 | 2 |
| 0 | 1 | 2 |
| 0 | 1 | 2 |
