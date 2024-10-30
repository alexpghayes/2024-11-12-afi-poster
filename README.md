---
output:
  pdf_document: default
  html_document: default
---

# Estimating peer influence: limitations of linear-in-means model

Linear-in-means models are widely used to investigate peer effects. Identifying peer effects in these models is challenging, but conditions for identification are well-known. However, even when peer effects are identified, they may not be estimable, due to an asymptotic colinearity issue: as sample size increases, peer effects become more and more linearly dependent.  We show that asymptotic colinearity occurs whenever nodal covariates are independent of the network and the minimum degree of the network is growing. Asymptotic colinearity can cause estimators to be inconsistent or to converge at slower than expected rates. We also demonstrate that dependence between nodal covariates and network structure can alleviate colinearity issues in random dot product graphs.

## Poster preview

![](poster.pdf)

in between for test

![](poster.png)

## Converting from PDF to TIFF or PNG for printing on online display

```sh
magick -density 200 -quality 80 -format tiff poster.pdf AlexHayes-AFFI2024.tiff
magick -density 250 -quality 85 poster.pdf AlexHayes-AFFI2024.png
```