# ADA Report and Thesis Proposal Template

This is a LaTeX template for ADA reports and thesis proposals in the Department
of Statistics & Data Science, Carnegie Mellon University. The Department does
not have strict formatting requirements, so use of this template is optional,
but it is a convenient way to format your work.

This template was created by Alex Reinhart.

To use this template, you can either:

- Make a copy of this repository under your own GitHub account by pressing the
  green "Use this template" button. Then you can clone the repository to your
  computer and work in it like any other Git repository.
- In the Releases section on the GitHub page for this template, download a Zip
  file containing the template. You can work on these on your computer or upload
  them to Overleaf.

Once you have the template on your computer, open `proposal.tex` and follow the
instructions inside.

If you'd like to make a reproducible report with R code embedded inside, the
[knitr](https://yihui.org/knitr/) package supports R code in LaTeX files. Save
`proposal.tex` as `proposal.Rnw` and open it in RStudio. R code chunks can be
written like this:

```
<<chunk-name, echo=FALSE>>=
# Your R code goes here
library(ggplot2)

ggplot(cars, aes(x = speed, y = dist)) +
  geom_point()
@
```

This works much like R Markdown, but entirely within LaTeX. RStudio has a button
to run the code and generate a PDF.
