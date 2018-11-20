# RSE
RSE is an R package (newest version: 1.3) developed by Youhua Chen and Tsung-Jen Shen for estimating the number of newly found rare species in additional ecological samples, 
based on species diversity information (abundance or incidence) in original ecological samples. 
The methods implemented in this R package include a Bayesian-weighted estimator and two unweighted estimators.
All the estimators have been described in detail in the following paper:

Shen TJ, Chen YH (2018) A Bayesian weighted approach to predicting the number of newly discovered rare species. Conservation Biology, doi: 10.1111/cobi.13253.


To install, please download the file RSE_1.3.tar.gz and save it into your local directory.
Open R software, and type the following command:

install.packages("your_local_directory/RSE_1.3.tar.gz",repos=NULL,type="source")

To use the RSE package in R, now load the package by typing the following command:

library(RSE)

After that the package has been loaded in R environment, for the assistance about each function and the associated demonstrating example, 
type the following command in R software (taking the function f.to.X() in the package as an example):

?f.to.X


For a quick reference, readers are recommended to download and read the RSE-vignette.pdf to learn how to use the package quickly. Further, readers are also encouraged to download and read the R-mannual.pdf for specific introductions about the functions and the examples demonstrated. 



Note: Since October 20th, RSE package is also available from CRAN repository, the link is https://CRAN.R-project.org/package=RSE. However, the latest updated version will be always posted in this Github repository.



------------------------------------------------------------------------------


Bug fixation reports:

2018-11-03：

RSE (version 1.3) fixes a bug on the bootstrapping procedure. Thanks Wenyan Zhang for reporting the bug.

2018-10-15:

RSE(version 1.2) fixes the following bugs:

1, Pred.Qk.BW and Pred.Fk.BW has been modified to restrict the loop runs from 1 to min(i,kmax) to avoid potential NA issue.

2, in Pred.abundance.rare function, k.show has been supplied for functions Pred.Fk.BW and Pred.Fk.unweighted.


-------------------------------------------------------------------------------


If you have any questions, please contact:


Prof. Youhua Chen, email: haydi@126.com;
Address: CAS Key Laboratory of Mountain Ecological Restoration and Bioresource Utilization & Ecological Restoration and Biodiversity Conservation Key Laboratory of Sichuan Province, Chengdu Institute of Biology, Chinese Academy of Sciences, Chengdu, 610041.


Prof. Tsung-Jen Shen, email: tjshen@nchu.edu.tw;
Address: Institute of Statistics & Department of Applied Mathematics, National Chung Hsing University, 250 Kuo Kuang Road, Taichung, 40227.
