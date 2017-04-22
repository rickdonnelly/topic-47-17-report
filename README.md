# Statewide and Megaregional Travel Forecasting Models
NCHRP Project 20-05, Synthesis Topic 47-17

This repository contains the code and data used to build the final report using LaTeX, as well as the current version of the document. It was built using TeXShop Version 3.77 running under macOS Sierra. It compiles using the [standard MacTeX-2016 distribution](https://tug.org/mactex/), and requires no special packages or additional utilities. It creates a single Acrobat Acrobat (.pdf) output file. 

Because of their size the graphics included in the document are stored separately. Both greyscale and color versions were created for the print and online versions of the report, respectively. In order to make it simple to generate a document with either the code expects to find the figures in the graphics folder. You should copy with the grayscale or color figures into that directory before compiling. Follow these steps to compile the report:

+ [Download the graphics](https://www.dropbox.com/s/635pssglb0924yk/topic47-17-latex-graphics.zipx?dl=0) and copy all of the files from either the greyscale or color folder into the graphics folder in this directory (i.e., the one that topic47-17.tex is located in). 
+ Compile `topic47-17.tex` (found in the root directory of this repository)
+ You can optionally compress the updated `topic47-17.pdf` using [Smallpdf](https://smallpdf.com/compress-pdf) or comparable utility. There is no loss in resolution of the output when using Smallpdf or Adobe Acrobat, but we have noticed that some other programs downgrade the embedded images, making smaller text unreadable. _Caveat emptor_.

The report is the final report that we submitted to NCHRP for publication. Please do not cite or distribute the document, as it is still awaiting publication. Please contact the authors ([Rick Donnelly](mailto:donnellyr@pbworld.com) and [Rolf Moeckel](mailto:rolf.moeckel@tum.de)) with any questions, and especially if you find errors in the manuscript. 
