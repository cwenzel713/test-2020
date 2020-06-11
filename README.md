## Normal Distribution

```r
rnorm (100)

```r
set.seed(59)
rnorm(100, 5, 1)

a <- rnorm(100, 5, 1)
png("rnorm100_qqnorm.png", units="px", width=1600, height=1600, res=300)
qqnorm(a)
dev.off ()
```
