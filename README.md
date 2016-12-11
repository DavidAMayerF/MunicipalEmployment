# MunicipalEmployment

The aim of the project is to analyze municipal economic dynamics as it can be ascertained from DENUE (2012 and 2016), a directory of mexican firms.

This data has been complemented with some population and migration data from the 2010 census and the 2015 count.

Delta6-PCAexploration.ipynb produces some variables using principal component analysis.

Delta7FeaturesAndLabels.ipynb organizes features and labels for the analysis. 

For now the focus will be on dx and dptot, rate of growth of first component of log((1 + firm numbers)(SE)) for 1 <= S <= 9 (one digit classification of sectors) and 1 <= E <= 7 (seven employment level categories), and rate of growth of population.

Delta9RandForDEPTHdif.ipynb uses the Random Forest Classifier to estimate "healthy growth", above 0.05 for firms and 0.01 for population.

Delta10RandForRegDEPTHdif.ipynb uses the Random Forest Regressor to predict same variables quantitatively.

TwinProcesses.pdf contains a full account of the project.

The TwinProcessesSummary powerpoint provides a guide into the motivation.


