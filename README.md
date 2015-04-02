This is a template for building a thesis for the University of Idaho. It is slightly modified from a UBC [template](https://github.com/richfitz/thesis-style) by Rich FitzJohn.

If you have [make](https://www.gnu.org/software/make/) installed, you can compile this template with `pdflatex` simply by downloading or cloning the repository and typing

```
make
```

If you don't have `make` on your computer, you can compile using the following series of commands
```
pdflatex thesis.tex
bibtex thesis.aux
pdflatex thesis.tex
pdflatex thesis.tex
```

Designed to work with Minon Pro -- see [here](https://gist.github.com/richfitz/2324707) for installation instructions for OSX (differnet platforms will require slightly different procedures to get Minion Pro up-and-running with Tex).  Will fall back on Palatino if Minion Pro is not available.
