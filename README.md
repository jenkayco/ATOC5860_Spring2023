# ATOC5860_Spring2023
code for ATOC5860 Objective Data Analysis Spring 2023
Prof. Jennifer E. Kay, University of Colorado, Jennifer.E.Kay@colorado.edu
Last updated: last updated April 27, 2023

All code uses python environment atoc5860env2023clean.yml

All data are available here: 
https://o365coloradoedu-my.sharepoint.com/:f:/g/personal/jeka1927_colorado_edu/Ejreu7Z76ZBDmnJwPi1K9J8BgcBisGcmGRwNKXRyPraCIw?e=aXoTfw

0) Lecture code in folder lecture_code

1) Application lab code in folder applicationlabs

Application Lab #1 files in the folder lab1 (hypothesis testing, bootstrapping)
ATOC5860_applicationlab1_bootstrapping.ipynb
ATOC5860_applicationslab1_ztest_ttest.ipynb
TS_timeseries_cesmle_1850.nc
TS_timeseries_cesmle_1920_2100.nc
nino34.long.anom.data.txt
snow_enso_data.csv

Application Lab #2 files in folder lab2 (regression)
ATOC5860_applicationlab2_AR1_Nstar.ipynb
ATOC5860_applicationlab2_AR1_regression_AO.ipynb
christman_2016.csv
monthly.ao.index.b50.current.ascii

Application Lab #3 files in folder lab3 (principle component analysis/empirical orthogonal function)
ATOC5860_applicationlab3_eof_analysis_cosineweightingLAST_cartopy.ipynb - EOF/PCA of Observed Sea Surface Temperatures
ATOC5860_applicationlab3_eigenfaces.ipynb - EOF/PCA of faces
Note: The data needed for lab3 (HadISST_sst.nc, att_faces.npy) are too big to upload to github.
Please download yourself from http://www.metoffice.gov.uk/hadobs/hadisst/data/download.html
or from https://o365coloradoedu-my.sharepoint.com/:f:/g/personal/jeka1927_colorado_edu/Ejreu7Z76ZBDmnJwPi1K9J8BgcBisGcmGRwNKXRyPraCIw?e=aXoTfw

4) Application Lab #4 files in folder lab4 (spectral analysis)
ATOC5860_applicationlab4_fft_EPICA.ipynb - spectral analysis of ice core data over many glacial cycles
edc3deuttemp2007.txt, edc3deuttemp2007_nohead.txt - ice core data
ATOC5860_applicationlab4_fft_mesa.ipynb - spectral analysis of weather data from the NCAR Mesa Lab Boulder, Colorado
mesa_data_2016-2021_withmissing.csv - weather data from NCAR Mesa Lab Boulder, Colorado available from https://o365coloradoedu-my.sharepoint.com/:f:/g/personal/jeka1927_colorado_edu/Ejreu7Z76ZBDmnJwPi1K9J8BgcBisGcmGRwNKXRyPraCIw?e=aXoTfw

5) Application Lab #5 files in folder lab5 (filtering)
ATOC5860_applicationlab5_check_python_convolution.ipynb - understand python functions used to smooth/filter in the time domain
ATOC5860_applicationlab5_synthetic_data_with_filters.ipynb - filter analysis of synthetic data
ATOC5860_applicationlab5_ENSO_mrbutterworth.ipynb - filter analysis of ENSO in a climate model
CESM1_LENS_Coupled_Control.cvdp_data.401-2200.nc - available from https://o365coloradoedu-my.sharepoint.com/:f:/g/personal/jeka1927_colorado_edu/Ejreu7Z76ZBDmnJwPi1K9J8BgcBisGcmGRwNKXRyPraCIw?e=aXoTfw

6) Application Lab #6 files in folder lab6 (machine learning)
ATOC5860_applicationlab6_cluster_mesa_data.ipynb - unsupervised machine learning (k-means clustering) of weather data from Boulder, Colorado
ATOC5860_applicationlab6_cluster_mesa_data_3clusters.ipynb - like ATOC5860_applicationlab6_cluster_mesa_data.ipynb but uses 3 instead of 4 clusters
NCAR_mesa_data_2016-2021_withmissing.csv - data needed for ATOC5860_applicationlab6_cluster_mesa_data.ipynb
supervised.ipynb - same as ATOC5860_applicationlab6_supervised_ML.ipynb; but runs on google colabs (preferred)
christman_2016.csv - data needed for ATOC5860_applicationlab6_supervised_ML.ipynb
ATOC5860_applicationlab6_supervised_ML.ipynb - supervised machine learning of weather data from Fort Collins, Colorado
environment.yml - environment needed for ATOC5860_applicationlab6_supervised_ML.ipynb
