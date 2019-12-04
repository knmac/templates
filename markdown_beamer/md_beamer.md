---
theme: metropolis
title: test pandoc beamer
subtitle: subtitle
author: Khoi-Nguyen Mac
institute: UIUC
date: 10/10/2019
toc: false
slide_level: 2
header-includes: \metroset{progressbar=frametitle,sectionpage=progressbar}
---

# Section 1

## Slide 1
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
