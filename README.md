# Pset-598-599 Format

This is an easy and quick template for problem sets for POLSCI 598
and POLSCI 599 classes. I highly encourage you to not solely rely
on this pre-made template, and to continue deepening your LaTeX
experience and usage. Quarto uses Pandoc to generate the PDF output.
Furthermore, all equations have to be typed using LaTeX markup
language. Quarto facilitates the integration with `R` for the output,
but does not solve all your problems.

```mermaid
flowchart LR;
Quarto-->Pandoc;
Pandoc-->LaTeX;
LaTeX-->PDF;
```

## Installing

To install the template, you can run the following command in your 
terminal in the directory you want to work for your current problem 
set.

```bash
quarto use template JozefRivest/pset-598-599
```

Otherwise, you can copy the whole template by clicking on the green 
`Code` button, then on Download ZIP. 

