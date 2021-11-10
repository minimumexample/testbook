---
title: "Testing installing packages from remotes"
date: "2021-11-10"
site: bookdown::bookdown_site
github-repo: minimumexample/testbook
---

# Plot


```r
library(ggplot2)
ggplot(mpg, aes(displ, hwy, colour = class)) + 
  geom_point()
```

<img src="index_files/figure-html/unnamed-chunk-1-1.png" width="672" />
