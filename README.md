# quant_trading - ideas and codes for quantitative trading

[TOC]

## pairs_trading  

### reading_material  
[multivariate approach](https://drive.google.com/open?id=0B3x7xDLSsPvJQ1BIZUM2UEI2V1E)
[OU approach](https://drive.google.com/open?id=0B3x7xDLSsPvJSDRkb0dWdTA3UGc)

### classical_approach  
1. normalize return  
$p=\frac{p-E [p] }{ \sigma }$
2. how to find the pairs?  
OLS and find the min squared error.  
max correlation of two normalized time series.  
3. trading signal  
when the absolute distance is larger than threshold, long the lower price one and short the higher price one.  
4. problem  
maybe only one is badly priced. there is no mechanism to prevent buying badly priced stocks.  

### multivariate_pairs_trading  
1. idea is if we find multivariate relations, it is less likely we buy a badly priced stock.  
2.  
