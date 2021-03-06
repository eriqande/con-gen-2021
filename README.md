Con-Gen 2021. Eric C. Anderson’s resources
================

## Wednesday, September 8, 2021

The presentation follows the narrative in the following html document:

  - <https://eriqande.github.io/con-gen-2021/bayes-mcmc-gtyperr-narrative.nb.html>

Within that notebook are links to the Shiny Apps I have written to play
with genotype likelihoods (as well as directions on how to use them). If
you want to get the associated R project, you can go to my directory on
the ConGen Box at:

  - <https://umt.box.com/s/n3x7v1hpqkf4h9glu41whxrqaostoqva>

and then download the `ngs-genotype-models` directory.

Or, you can also just download it or clone it from GitHub:

  - <https://github.com/eriqande/ngs-genotype-models>

Once you have that `ngs-genotype-models` directory you can open the
RStudio project `ngs-genotype-models.Rproj` within the directory and
then open any one of the Rmd documents in the top level directory (named
`001-allele-freq-estimation.Rmd`,
`002-genotype-likelihoods-from-reads.Rmd` and
`003-read-inference-gsi.Rmd` in RStudio). RStudio will prompt you to
install any needed packages if you don’t already have them (namely
`tidyverse` and `shiny`). After that, clicking the `Run Document` button
at the top of the document will create a Shiny App for your Hands-On
excercises.

These don’t run on the ConGen Shiny Server, so you have to run these on
your personal computer.

And, *only as a last resort*, if you can’t get the Shiny Apps working in
RStudio on your computer, you can visit their pages on `shinyapps.io`:

  - <https://eriqande.shinyapps.io/001-allele-freq-estimation/>
  - <https://eriqande.shinyapps.io/002-genotype-likelihoods-from-reads/>
  - <https://eriqande.shinyapps.io/003-read-inference-gsi/>

### If we have additional time

I am expecting that the above will take most of the time we have
together this morning, but if we have some leftover time, we could talk
about gbs miscall rates in RAD data before probabilistic genotype
calling was used, any my R package ‘whoa’.

Lecture slides for this:

<https://eriqande.github.io/con-gen-2021/gbs-miscall.pdf>

The computer practical accompanying this segment is in the box directory
in the RStudio Project `whoa-practical-session`. This will run on the
RStudio Server (if you move the `whoa-practical-session` directory to
your own home directory). Fire it up and run through
`001-whoa-first-steps.Rmd`.
