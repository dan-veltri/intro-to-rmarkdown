## Intro to R Markdown for Data Science

An intro crash course for using R-markdown!

Feel free to post your questions on this Google Document: [https://docs.google.com/document/d/1C0G0qHdxPKC_tUsb8OtlATDN0Zslb4T2xeWjZ9dyGMI/edit?usp=sharing](https://docs.google.com/document/d/1C0G0qHdxPKC_tUsb8OtlATDN0Zslb4T2xeWjZ9dyGMI/edit?usp=sharing)


*Presentation Slides:*
* [IntroRMarkdown_NIAID_32421_PPT.zip](IntroRMarkdown_NIAID_32421_PPT.zip) [PowerPoint]
* [IntroRMarkdown_NIAID_32421_PDF.zip](IntroRMarkdown_NIAID_32421_PDF.zip) [PDF]

*Recommended Handouts:* [GitHub's Markdown Cheatsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf) | [R-Studio's RMarkdown Cheatsheet](https://github.com/rstudio/cheatsheets/raw/master/rmarkdown-2.0.pdf)

### Installation:
Looking to the run examples on your own machine? First install R-studio and then the latest versions of the following packages:

* `dplyr`
* `knitr`
* `rmarkdown`
* `flexdashboard`
* `reticulate`
* `plotly`
* `kableExtra` <-- This may not install correctly on the server
* `leaflet`
* `mapview`

The following packages require a followup command to install software. These might need admin rights on your machine to install correctly! 
`webshot` <-- Installs PhantomJS - only needed if not already installed on machine
Then run in R: `webshot::install_phantomjs()` 

`tinytex` <-- Installs LaTeX - only needed if not already installed on machine
Then run in R: `tinytex::install_tinytex()`

You may need to ssh into the server, type `R` to enter an R session, and install the packages with the following line:
`install.packages(c("dplyr","knitr","rmarkdown","flexdashboard","reticulate","plotly","leaflet","mapview"))`

Notice that `kableExtra` has been left out to prevent problems. You will also need to type the `tinytex::install_tinytex()` line mentioned above after the packages install. After this the R Shiny server should be able to run most of the basic examples.

*Note:* If installing on your own machine, it might be easier on your machine to install LaTeX using a different installer rather than via TinyTex. [See this page for more info!](https://latex-tutorial.com/installation/) 
