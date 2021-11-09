# Plots


```r
library(ggplot2)

ggplot(mpg, aes(displ, hwy, colour = class)) + 
  geom_point()
```

<img src="plot_files/figure-html/unnamed-chunk-1-1.png" width="672" />
