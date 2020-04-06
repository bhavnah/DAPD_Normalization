# DAPD Method
Digital Adjustment of Plant Devopment (DAPD) is a method that sychronize shoot phenotypic measurements. It uses the plant leaf number to normalizes time-series measurements such as the projected rosette area and leaf area. This method improves accuracy by decreasing the statistical dispersion of time-series of quantitative traits. Also, it can identify more outliers than any other central tendency technique on the non-normalised dataset.

The DAPD method has three modules: Rosette segmentation, Leaf segmentation and normalization. 
- _Rosette segmentation module_ uses multiple image processing algorithms to extract the rosette area and remove the background. 
- _Leaf segmentation module_ extracts individual leaf from the rosette. 
- _Normalization module_ calculates a reference time-line using Bayesian inference at multiple time points of the time-series measurements, which include rosette area, leaf size and number.



