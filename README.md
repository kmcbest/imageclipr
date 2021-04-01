## imageclipr
[![CRAN version](http://www.r-pkg.org/badges/version/imageclipr)](https://cran.r-project.org/package=imageclipr)

RStudio Addin: Copy images from clipboard into RMarkdown .Rmd files.

![Usage of imageclipr](usage.gif)

## Installation
`devtools::install_github('kmcbest/imageclipr')`

## Dependencies
R packages `library(rstudioapi)`,  (`library(rmarkdown)` for markdown files)

For linux [xclip](https://github.com/astrand/xclip) is required.
For debian, ubuntu,... install it with:
```
sudo apt-get install xclip 
```

## Open issues
- can not: 

-- copy and paste image and text together

-- copy and paste an image by copying the file in the explorer

## Technical walkthrough
(highlevel): https://stackoverflow.com/questions/55541345/copy-and-paste-an-image-from-clipboard-to-rmarkdown-rmd-code



## Usage

### Select the addin
![Addin selection](clipboardImage_5.png)

### Adding a keyboard shortcut (Recommended)
In RStudio go to Tools - Modify Keyboard Shortcuts...

![Find Shortcuts](clipboardImage_1.png)

![Modify Shortcuts](clipboardImage_2.png)


(This project is part of my life long application to RStudio :))
