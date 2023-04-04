# Dynamic Topological Data Analysis (TDA)

This is the material for the Python tutorial on Dynamic TDA that will be given at the 20th IEEE International Symposium on Biomedical Imaging (ISBI 2023), organized jointly by the IEEE Signal Processing Society and the IEEE Engineering in Medicine and Biology Society, which will be held in Cartagena de Indias, Colombia, April 18-21, 2023.

To make this tutorial on Dynamic TDA as friendly as possible, we base it on the Scikit-TDA project. More specifically, we will use the Ripser and Persim libraries as the backbone of our code.

---

The outline of the tutorial is as follows:
- Persistence homology (PH) on point cloud data with persistence diagrams (PDs)
- Wasserstein and Bottleneck distance computations between PDs
- Persistence landscapes (PLs)
- Time delay (TDE) and sliding window (SWE) embeddings for time series data
- Application to Epileptic Seizure EEG data set

This TDA tutorial is user friendly and aims to illustrate the key concepts behind dynamic TDA. It includes multiple examples with simulated data sets, such as the sphere or a torus.

---

I would like to acknowldege Dr. Beth Malow, from the Department of Neurology at Vanderbilt University (formerly with the Department of Neurology at University of Michigan) for sharing the Epileptic Seizure EEG data set with us.
You need to acknowldege Dr. Beth Malow and cite the following papers if you plan to use this data set in your own research projects.
- Ombao, H., Raz, J., von Sachs, R. and Malow, B. (2001). Automatic Statistical Analysis of Bivariate Non-Stationary Time Series, J Amer Stat Assoc, 96, 543-560.
- Ombao, H., von Sachs, R. and Guo, W. (2005). SLEX Analysis of Multivariate Non-Stationary Time Series, J Amer Stat Assoc, 100, 519-531.
- Wang Y, Ombao H and Chung M. (2018). Persistence Landscape with Application to Epileptic Seizure Encephalogram Data. Annals of Applied Statistics, 12 ,1506-1534.
- Euan C, Sun Y and Ombao H. (2019). Coherence-based time series clustering for brain connectivity visualization. Annals of Applied Statistics, 13, 990-115.
- Schroeder A and Ombao H. (2019). FreSpeD: Frequency-Specific Change-Point DetectionMethod in Multi-Channel Epileptic Seizure EEG Data. Journal of the AmericanStatistical Association, 114: 115-128.