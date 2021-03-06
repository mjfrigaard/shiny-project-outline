Shiny application project outline
================

This is a rough attempt to formalize an outline for documenting a shiny
application.

## Motivation

I noticed after creating a shiny application, I had a hard time keeping
track of `ui.R` and `server.R` components using `#comments`, so I
created a parent folder and R project (.Rproj), then started a
`README.Rmd` file to document the contents in each file.

    |-- shiny-project > *this is the parent folder file*
        |-- App 
        |   |-- App.Rproj
        |   |-- data
        |   |   |-- 2019-02-20.RData
        |   |   |-- data-file-01.csv
        |   |   |-- data-file-02.csv
        |   |   |-- data-file-03.csv
        |   |-- helpers.R
        |   |-- server.R
        |   |-- ui.R
        |   |-- www
        |       |-- picture-01.jpg
        |       |-- logo-02.jpg
        |       |-- style.css
        |-- README.Rmd -> *this is the documentation file*
        |-- README.md
        |-- data -> *data files for the app are also stored here*
        |   |-- 2019-02-20.RData
            |-- data-file-01.csv
            |-- data-file-02.csv
            |-- data-file-03.csv
        |-- images -> *image files for the app*
        |   |-- picture-01.jpg
        |   |-- logo-02.jpg
        |   |-- style.css
        |-- shiny-project-appndx-a.Rmd -> *appendix for additional descriptions*
        |-- shiny-project.Rproj
        |-- rsconnect
            |-- documents
                |-- App
                |   |-- shinyapps.io

This is really the beginning of an idea, and I have only implemented it
on a few projects (see example
[here](https://mjfrigaard.github.io/seg-shiny-v-1-3-1/)).

I would love feedback from anyone\!
