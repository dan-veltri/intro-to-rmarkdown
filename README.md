## Intro to R Markdown for Data Science

An intro crash course for using R-markdown!

Feel free to post your questions in [this Google Document](https://docs.google.com/document/d/1C0G0qHdxPKC_tUsb8OtlATDN0Zslb4T2xeWjZ9dyGMI/edit?usp=sharing)!


*Presentation Slides:*
* [IntroRMarkdown_NIAID_32421_PowerPoint.zip](https://github.com/dan-veltri/intro-to-rmarkdown/blob/master/IntroRMarkdown_NIAID_32421_PowerPoint.zip) [PowerPoint]
* [IntroRMarkdown_NIAID_32421_PDF.zip](https://github.com/dan-veltri/intro-to-rmarkdown/blob/master/IntroRMarkdown_NIAID_32421_PDF.zip) [PDF]

*Recommended Handouts:* [GitHub's Markdown Cheatsheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf) | [R-Studio's RMarkdown Cheatsheet](https://github.com/rstudio/cheatsheets/raw/master/rmarkdown-2.0.pdf)

### Installation:
Looking to the run examples on your own machine? First install R-studio and then the latest versions of the following packages:

* `dplyr`
* `knitr`
* `rmarkdown`
* `flexdashboard`
* `reticulate`
* `plotly`
* `kableExtra`
* `leaflet`
* `mapview`

The following packages require a followup command to install software. These might need admin rights on your machine to install correctly! 
`webshot` <-- Installs PhantomJS - only needed if not already installed on machine
Then run in R: `webshot::install_phantomjs()` 

`tinytex` <-- Installs LaTeX - only needed if not already installed on machine
Then run in R: `tinytex::install_tinytex()`


On the R Studio Server - you can use the preinstalled packages by typing the following in the console:

`old_path <- Sys.getenv("PATH")`

`Sys.setenv(PATH = paste(old_path, "/biocompace/bin", sep = ":"))`

If you want to install the packages in your own local machine/directory, install the packages with the following line (and then run the `install_tinytex` function above):
`install.packages(c("dplyr","knitr","rmarkdown","kableExtra","flexdashboard","reticulate","plotly","leaflet","mapview"))`

*Note:* If installing on your own machine, it might be easier on your machine to install LaTeX using a different installer rather than via TinyTex. [See this page for more info!](https://latex-tutorial.com/installation/) 
