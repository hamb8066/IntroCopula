# Dependence modelling with copula in R
These codes are collected and gathered by [H.A.Mohtashami-Borzadaran](https://hamb8066.github.io/homepage) & [N. Doodman](https://www.researchgate.net/profile/Neda_Doodman) with the supervision of [Prof. M. Amini](http://m-amini.profcms.um.ac.ir).

# Introduction
In probability theory and statistics, a copula is a multivariate cumulative distribution function for which the marginal probability distribution of each variable is uniform on the interval [0, 1]. Copulas are used to describe the dependence between random variables. Their name comes from the Latin for "link" or "tie", similar but unrelated to grammatical copulas in linguistics. Sklar's theorem states that any multivariate joint distribution can be written in terms of univariate marginal distribution functions and a copula which describes the dependence structure between the variables. Copulas are popular in high-dimensional statistical applications as they allow one to easily model and estimate the distribution of random vectors by estimating marginals and copulae separately. There are many parametric copula families available, which usually have parameters that control the strength of dependence. Copulas are applied in many fields such as:  
* Quantitative finance  
* Civil engineering  
* Reliability engineering  
* Warranty data analysis  
* Turbulent combustion  
* Medicine  
* Signal processing  
* etc.  
See the Wikipedia page on [copula](https://en.wikipedia.org/wiki/Copula_(probability_theory)) and [Vine-Copula](https://en.wikipedia.org/wiki/Vine_copula).

# Some References
* Nelsen, R. B. (2007). [An introduction to copulas.](https://www.springer.com/gp/book/9780387286594) Springer Science & Business Media.  
* Joe, H. (2014). [Dependence modeling with copulas.](https://www.routledge.com/Dependence-Modeling-with-Copulas/Joe/p/book/9781466583221) CRC press.  
* Durante, F., & Sempi, C. (2015). [Principles of copula theory.](https://www.routledge.com/Principles-of-Copula-Theory-1st-Edition/Durante-Sempi/p/book/9781439884423) CRC press.  
* Matthias, S., & Jan-frederik, M. (2017). [Simulating Copulas: Stochastic Models, Sampling Algorithms, and Applications.](https://www.worldscientific.com/worldscibooks/10.1142/10265).  
* Hofert, M., Kojadinovic, I., Mächler, M., & Yan, J. (2019). [Elements of copula modeling with R.](https://www.springer.com/gp/book/9783319896342) Springer.  
<sup> [Here](http://copula.r-forge.r-project.org/book) you can find R-codes for this book. </sup>  
* Czado, C. (2019). [Analyzing Dependent Data with Vine Copulas.](https://www.springer.com/gp/book/9783030137847) Lecture Notes in Statistics, Springer.  
<sup> [Here](https://www.groups.ma.tum.de/en/statistics/people/claudia-czado/r-code-to-analyzing-dependent-data-with-vinecopulas/) you can find R-codes for vine-copulas </sup>  

# Used R Packages
* The [copula](https://cran.r-project.org/web/packages/copula/index.html) package.
* The [Vine-Copula](https://cran.r-project.org/web/packages/copula/index.html) package.
* The [kdevine](https://github.com/tnagler/kdevine) package.

## Exploratory data analysis

## Univariate Fitting  
- Parametric  

- Non-parametric  


## Dependence measures
- Pearson Rho
- Spearman's Rho
- Kendall's Tau

## Copula models
- Archimedean copulas 
- Nested Archimedean copulas
- Elliptical copulas
- Extreme-value copulas
- Frechet-Hoeffding copula
- Khoudraji copula
- Rotation of copulas
- Mixture of copulas

## Decomposition of Sklar theorem


## Inference on U-data



```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

