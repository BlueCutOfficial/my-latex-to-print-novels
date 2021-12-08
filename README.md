# My LaTeX to print novels
This repository is not a project to install. Its purpose is to share the LaTeX configuration I use to print French novels. 

## About 

### From LaTeX to PDF
Most printers require PDF or Word formats to print novels.

[Texmaker](https://www.xm1math.net/texmaker/) is a fantastic editor to write a book in LaTeX then easily build a PDF out of it. 

LaTeX makes quite simple to configure a set of rules and margins that can apply to any book. The first one is the hardest, then you earn some precious time on next projects ;)

### Fit French
The configuration I share in this repo is meant to be a source of inspiration for any project, but it fits the design of a French novel.

Rules are quite different from one language to another. For instance, in English books, the first paragraph of a chapter is not indented ; in French books, it is. I don't know all possible differences in all possible languages, but note I built this config for my French books.

## Features

### Overview

This configuration shows how to:
- Add empty white pages where they are needed
- Move a block at the bottom of the page to write the editor's data and other legal stuff
- Customize "maketitle" to display a custom title page
- Control margins and let the 2cm required by printers on each side
- Deactivate word-break at the end of the line (as text is justified)
- Not add a white page if a chapter ends on an odd page
- Manually reset the page number (because the empty white page doesn't count)
- Not display page number on the editor's data page
- Not display page number on end of chapter pages
- Customize the table of contents name
- Customize the table of content style to make it a little smaller and add dots

### Demo

Here is the output PDF built with Texmaker and the set of LaTeX files: [Demo PDF](https://github.com/BlueCutOfficial/my-latex-to-print-novels/blob/main/tex/papier.pdf)
