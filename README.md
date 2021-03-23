## Intro to R Markdown for Data Science

An intro crash course for using R-markdown!


*Presentation Slides:* [IntroRMarkdown_NIAID_91620.zip](IntroRMarkdown_NIAID_91620.zip)

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

*Note:* It might be easier on your machine to install LaTeX using a different installer rather than via TinyTex. [See this page for more info!](https://latex-tutorial.com/installation/) 
