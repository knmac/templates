---
title: Presentation Title
subtitle: Subtitle
author: Khoi-Nguyen C. Mac
date: 12/34/5678

classoption: aspectratio=169
slide_level: 2
toc: true

header-includes: 
	- \usepackage{uiuc_theme, symbols, bbm}
	- \titlegraphic{\centering \includegraphics[height=2cm]{ui_logo.png}}
	- \AtBeginSection[]{\begin{frame}\vfill \centering \begin{beamercolorbox}[sep=8pt,center,shadow=true,rounded=true]{title} \usebeamerfont{title}\insertsectionhead \par \end{beamercolorbox} \vfill \end{frame} }
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
$$E=mC^2, E \in \R$$


## Slide 4
| a | b | c |
|---|---|---|
| 0 | 1 | 2 |
| 0 | 1 | 2 |
| 0 | 1 | 2 |
