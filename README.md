# Quiz13

### 1. (5 points)
 Calculate F(d) or G(d) for a CSR Poisson process with constant spatial intensity lambda. Explain the result.
 
### 2. (5 points)
The following code will create a QQ-plot for a simulated CRS that compares a border corrected estimate of F with the theoretical estimate. Include a simulation for a repulsive process (hint: stratified sampling) and a clustering process. Comment on the qqplot.
```{r}
F.CRS <- Fest(ppp(runif(100),runif(100)))
qqplot(F.CRS$theo, F.CRS$rs)
```
