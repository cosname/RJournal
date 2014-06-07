To generate PDF for The R Journal, you have to install the [preview version of RStudio](http://www.rstudio.com/ide/download/preview), then install a few packages in R:

```s
if (!require('devtools')) install.packages('devtools')
devtools::install_github(c('rstudio/rmarkdown', 'rstudio/rticles'))
```

Open the Rmd file in RStudio, click the `Knit` button, then rock and roll!
