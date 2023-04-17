---
date: "2016-04-27T00:00:00Z"
external_link: ""
image:
 # caption: Photo by rawpixel on Unsplash
  focal_point: Smart
links:
- icon: github
  icon_pack: fab
  name: 
  url: 
#slides: example
summary: Package presentation.
tags:
- Deep Learning
title: Risk Management blog 
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
# output:
#   blogdown::html_page:
#     toc: true
output:
  blogdown::html_page:
    toc: true
---
# Material 1: Building packages code

To build package use these commands:

```r
 library(devtools)
```

```
## Warning: le package 'devtools' a été compilé avec la version R 4.2.3
```

```
## Le chargement a nécessité le package : usethis
```

```r
 library(usethis) 
```
- usethis::use_r("nomdufichier") : to add R file and write function
- devtools::load_all()  : to load all related functions to yours
- devtools::install() : to install your package
- devtools::document()   : to document your package using roxygen
- usethis::create_package() : to directly create package
- usethis::use_git() : to use package version control vith github 
- devtools::load_all() :  to load all source functions to be able to test package
- devtools::check()	: to check our package
- use_data_raw() 	: create file to build data
- usethis::use_data(my data, compress="xz"):  to add data to my package
- use_package("add any package you need") : add any package to import from to description file


## build graphs






