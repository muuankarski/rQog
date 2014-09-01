# rqog-package


## Installation


```r
library(devtools)
install_github(repo = "rqog", username = "ropengov")
library(rqog)
```


## Examples

See the preliminary vignette for more examples

- [ropengov.github.io/rqog/vignettes/rqog_tutorial.html](http://ropengov.github.io/rqog/vignettes/rqog_tutorial.html)


```r
library(rqog)
# Reading the data
dat <- read_qog(which.data = "standard", data.dir = "datafolder")
```


