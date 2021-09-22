# Credit_Risk_Analysis
M17
## Overview

This project set out to study the credit history using machine learning methods. The machine learning learns the results of the an loan and the variables associated with it.

## Result

- Oversampling
	- Naive Random Oversampling
		- accuracy: 0.6371559776417305
	- SMOTE Oversampling
		- accuracy: 0.6630080161898323
- Undersampling
	- ClusterCentroids resampler
		- 0.5442077123989293
- Combination Sampling
	- SMOTEENN
		- 0.6320717636543822
- Ensemble Learners
	- Balanced Random Forest Classifier
		- 0.7885466545953005
	- Easy Ensemble AdaBoost Classifier
		- 0.9316600714093861

## Summary

We found that Easy Ensemble AdaBoost Classifier produces the pest accuracy of prediction, and thus conclude that said method is preferred.
