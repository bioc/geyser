# geyser 0.99.4

* xlab text matches slot selected
* factor order respected for (SINGLE) sample grouping in plot
* optional color for a single column 

# geyser 0.99.3

* updated bslib requirement to >= 0.6.0
* replaced a "=" with "->"
* fixed empty comma error in the Shiny UI
* tweak wording and plot size in the plotting view

# geyser 0.99.2

* addressing https://github.com/Bioconductor/Contributions/issues/3107 - Thanks 
* replaced T/F with TRUE/FALSE
* fixed bug in vignette example (removed unnecessary `SummarizedExperiment` call) - Thanks @federicomarini
* added inst/extdata/make_tiny_rse.R which reproduces the `tiny_rse` example data
* changed vignette style to BiocStyle::html_document  
* updated DESCRIPTION with urls
* reduce full import of outside packages
* Expanded unit testing suite for the box plot and heatmap generating functions
* lightly refactored the internal .exp_plot and .hm_plot functions to stop weird errors with testthat unit testing

# geyser 0.99.1

* fixed bug in vignette yaml

# geyser 0.99.0

* submitted to Bioconductor

# geyser 0.30.0

* Added a `NEWS.md` file to track changes to the package.
* Restructure ui.R/server.R to put the code directly into `geyser::geyser.R` to 
better match bioconductor style
* Better error handling for low value rows
* Removed one "in app" guide as the info is in the vignette 
