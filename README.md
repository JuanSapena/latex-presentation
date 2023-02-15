# LaTeX Template for Academic Presentations

This repository contains a minimalist template to write academic presentations with LaTeX Beamer. 

## Template documentation

The template is documented at https://pascalmichaillat.org/d1/.

## Template overview

+ The font for text, roman math, and numbers is [Source Sans Pro](https://fonts.google.com/specimen/Source+Sans+Pro).
+ The font for Greek and calligraphic math is [Euler](http://luc.devroye.org/fonts-26139.html).
+ No colors are used in the text (only black/gray) to reduce distraction.
+ Colors are reserved for graphs and alerts.
+ Margins, spacing, and font size are set for comfortable reading.
+ There are no frills at the periphery of the slides.

## Template files

The repository contains files to produce a minimalist presentation with LaTeX Beamer. The template was developed with the MacTeX-2021 distribution.

+ `presentation.tex` –  LaTeX file containing the skeleton of the presentation. Fill it out with the content of your presentation. Compile it with pdfTeX.
+ `presentation.sty` –  LaTeX style file collecting all the formatting commands. Must be included in the same folder as `presentation.tex`.
+ `figures.pdf` – PDF file with all the figures included in the presentation. Replace the figures with your own figures—one per page.
+ `presentation.pdf` – PDF file produced by compiling `presentation.tex` with pdfTeX. This file is not required to use the template; it only illustrate the output of the template.

## Related resources

+ [This LaTeX template](https://github.com/pmichaillat/latex-paper) produces minimalist academic papers following the same principles, and with a similar general appearance, as this presentation template. 
+ [This LaTeX style file](https://github.com/pmichaillat/latex-math) contains commands to easily typeset mathematical expressions. It can be used in combination with this presentation template to make it easier to type and read math.

## License

The content of this repository is licensed under the terms of the [MIT License](https://opensource.org/license/mit-license-php/).
