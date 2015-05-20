# datascience-coursera
Datascience Coursera Stuff

## Useful R commands
### Installation of packages
* a <- available.packages(); head( rownames(a), 4)
* install.packages("slidefy")
* install.packages(c("slidefy","ggplot2"))
 
Bioconductor
* source("http://bioconductor.org/bioclite.R")
* biocLite
* biocLite(c("Genomicfeatures","AnnotationDbi"))

Use a package
* library(ggplot2)  accesses the package
* search()
* 

Reading/Writing Data
* read.table / write.table
* read.csv
* readLines / writeLines
* source /  dump
* dget / dput
* load / save          ' binary
* unserialize / serialize    ' binary



### Rtools
http://cran.r-project.org/bin/windows/Rtools
install.packages("devtools")
library(devtools)


### Data
* class(data)
* dim(data)
* nrow(data)
* ncol(data)
* head(data,10)  ## first 10 lines
* tail(data,10)  ## last 10 lines
* table(data$column)
* str(data)    ## structure of table.




 

