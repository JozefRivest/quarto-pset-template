# Pset-598/599 Format

This is an easy and quick template for problem sets for POLSCI 598
and POLSCI 599 classes. I highly encourage you to not solely rely
on this pre-made template, and to continue deepening your LaTeX
experience and usage. 

Quarto uses Pandoc to generate the PDF output. The flowchart below
illustrates the process that leads to the creation of a PDF file
using Quarto. Furthermore, all equations have to be typed using
LaTeX markup language. Quarto facilitates the integration with `R`
for the output, but does not solve all your problems. Plus, Quarto 
*does not* have a live-share option to collaborate on projects like 
Overleaf does. Hence, Quarto can be helpful, but should not hinder
your learning of \LaTeX. 

```mermaid
flowchart LR
Pandoc-- Extract syntax from Quarto file to create a new .tex file --> LaTeX;
LaTeX -- Compile to --> PDF;
```

## Installing

To install the template, you can run the following command in your 
terminal in the directory you want to work for your current problem 
set.

```bash
cd ~/directory/where/I/want/to/work

quarto use template JozefRivest/pset-598-599
```

Otherwise, you can copy the whole template by clicking on the green 
`Code` button, then on Download ZIP. 

Once you have the files and ready to work, you can do your problem 
set using the [template.qmd](template.qmd) file. Remove what you 
don't need and start to work!

For an example of the final output, please look at [template.pdf](template.pdf).
