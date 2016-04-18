# **CARS-PLS** #

# **Most recent versions are available at:** #

**The updated version is available only at: http://www.libpls.net**



By employing the simple but effective principle ‘survival of the fittest’ on which Darwin’s Evolution Theory is based, a novel strategy for selecting an optimal combination of key wavelengths of multi-component spectral data, named Competitive Adaptive Reweighted Sampling (CARS), is developed. Key wavelengths are defined as the wavelengths with large absolute coefficients in a multivariate linear regression model, such as partial least squares (PLS).The absolute values of regression coefficients of PLS model are used as an index for evaluating the importance of each wavelength. Then, based on the importance level of each wavelength, CARS sequentially selects N subsets of wavelengths from N Monte Carlo (MC) sampling runs in an iterative and competitive manner. In each sampling run, a fixed ratio (e.g. 80%) of samples are first randomly selected to establish a calibration model. Next, based on the regression coefficients, a two-step procedure including exponentially decreasing function (EDF) based enforced wavelength selection and adaptive reweighted sampling (ARS) based competitive wavelength selection is adopted to select the key wavelengths. Finally, cross-validation (CV) is applied to choose the subset with the lowest root mean square error of CV (RMSECV). The performance of the proposed procedure is evaluated using one simulated dataset together with one near infrared dataset of two properties. The results reveal an outstanding characteristic of CARS that it can usually locate an optimal combination of some key wavelengths which are interpretable to the chemical property of interest.
http://carspls.googlecode.com/files/LOGO.JPG

# **Key words** #
Variable selection; Monte Carlo; adaptive reweighted sampling; model sampling; near infrared; multivariate calibration

# **Paper** #
CARS is originally describled in:

http://carspls.googlecode.com/files/CARS.pdf

# **Implementation** #
We have implemented the algorithm of CARS in both MATLAB and R, which can be freely available at:

(1). R package for LINUX

http://carspls.googlecode.com/files/carspls_1.0.0.tar.gz

(2). R package for WINDOWS

http://carspls.googlecode.com/files/carspls_1.0.0.zip

(3). MATLAB package for WINDOWS

http://code.google.com/p/carspls/downloads/detail?name=CARS_V1.50.rar&can=2&q=


# **Related links** #
(1). **Model Population Analysis**(MPA) has recentrly been proposed as a general framework for developing chemometrics/bioinformatics methods. Details on MPA can be found at:

http://code.google.com/p/mpa2010/



(2).Based on model population anlaysis, we recently also developed a new method, called **subwindow permutation analysis(SPA)**,for variable selection in classification. Compared to CARS, SPA has clear **statistical meaning** and can compute a **_conditional p-value_** for each variable which is then used to calculate the **COditional Synergetic Score(COSS)** used for ranking variable. SPA is a very **refreshing** method. The source code of SPA in MATLAB and R can be freely available at:

http://code.google.com/p/spa2010/


(3).Also,CARS has been combined with PLSLDA for selecting the most distriminating subset of variables.CARS-PLSLDA has been successfully employed in our study to identify the informative variables of high dimensional **MALDI-TOF** data and **type 2 diabetes mellitus** data. The source codes of CARS-PLSLDA in both **MATLAB** and **R** could be freely available at:

http://code.google.com/p/cars2009

# **Reference** #
(1).  Hongdong Li, Y izeng Liang, Qingsong Xu, Dongsheng Cao, Key wavelengths screening using competitive adaptive reweighted sampling method for multivariate calibration, Anal Chim Acta 2009, 648(1):77-84

(2).  Tan BB, Liang YZ, Yi LZ, Li HD etal: Identification of free fatty acids profiling of type 2 diabetes mellitus and exploring possible biomarkers by GC–MS coupled with chemometrics. Metabolomics 2009.DOI:10.1007/s11306-009-0189-8

(3).  Hongdong Li, Yizeng Liang etal, Model Population Analysis for variable selection, Journal of chemometrics,DOI: 10.1002/cem.1300.

# **Contact** #
yizeng\_liang@263.net

lhdcsu@gmail.com

