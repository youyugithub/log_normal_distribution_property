# log_normal_distribution_property

```
mu<-2.3
sigma<-1.6
xx<-rnorm(10000000)
c(mean(exp(mu+sigma*xx)),exp(mu+sigma^2/2))
c(mean(xx*exp(mu+sigma*xx)),sigma*exp(mu+sigma^2/2))
c(mean(xx^2*exp(mu+sigma*xx)),(1+sigma^2)*exp(mu+sigma^2/2))
```
