# DAPD_Normalization
Digital Adjustment of Plant Devopment (DAPD) is a method that sychronize shoot phenotypic measurements. It uses the plant leaf number to normalizes time-series measurements such as the projected rosette area and leaf area. This method improves accuracy by decreasing the statistical dispersion of time-series of quantitative traits. Also, it can identify more outliers than any other central tendency technique on the non-normalised dataset.

DAPD has three modules: Rosette segmentation, Leaf segmentation and normalization. 
- ### _Rosette segmentation_ uses multiple image processing algorithms to extract the rosette area and remove the background. 

- ### _Leaf segmentation module extracts individual leaf from the rosette. 
3)The normalization module calculates a reference time-line using Bayesian inference at multiple time points of the time-series measurements, which include rosette area, leaf size and number.



