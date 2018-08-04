# RSE
RSE is an R package (version 1.1) developed by Youhua Chen and Tsung-Jen Shen for estimating the number of newly found rare species in additional ecological samples, 
based on species diversity information (abundance or incidence) in original ecological samples. 
The methods implemented in this R package include a Bayesian-weighted estimator and two unweighted estimators.
All the estimators have been described in detail in the following paper:

Shen TJ, Chen YH (2018). Predicting the number of newly discovered rare species: a Bayesian weight approach. Conservation Biology, In press.


To install, please download the file RSE_1.1.tar.gz and save it into your local directory.
Open R software, and type the following command:

install.packages("your_local_directory/RSE_1.1.tar.gz",repos=NULL,type="source")

To use the RSE package in R, now load the package by typing the following command:

library(RSE)

After that the package has been loaded in R environment, for the assistance about each function and the associated demonstrating example, 
type the following command in R software (taking the function f.to.X() in the package as an example):

?f.to.X


For a quick reference, readers are recommended to download and read the RSE-vignette.pdf to learn how to use the package quickly. Further, readers are also encouraged to download and read the R mannual for specific introductions about the functions and the examples demonstrated. 
