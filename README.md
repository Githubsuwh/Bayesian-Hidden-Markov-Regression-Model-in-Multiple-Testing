# Bayesian-Hidden-Markov-Regression-Model-in-Multiple-Testing
Bayesian Hidden Markov Regression Model in Multiple Testing for PHMM-HO and PHMM-HE

Shared code for the Poisson hidden Markov Model with homogeneous covariate effects (PHMM-HO) and Poisson hidden Markov Model with heterogeneous covariate effects (PHMM-HE) for both simulation studies and case study. The real data set people flow in and out of building is collected by University of California (Irvine), School of Information and Computer Sciences. Three zip documents are R code for simulation study for PHMM-HO and PHMM-HE, and the case study with PHMM, PHMM-HO and PHMM-HE. 

A summary for the R files included in the zip documents:
1. 'ML_Function_PHMM-HO.R': R function for the PHMM-HO 
2. 'ML_Function_PHMM-HE.R': R function for the PHMM-HE 
3. 'Function for Poisson Package.R': R function for PHMM to compare with PHMM-HO/PHMM-HE in the simulation study. The R code for MCMC and estimated marginal likelihood are the same for two regression model. The simulated data for two regression model are different.
4. 'PReg-HMM-People_Count.R': R code for case study with people flow in and out of building using PHMM and PHMM-HO.
5. 'CalIt2_Count.csv': data set used (people flow in and out of building https://archive.ics.uci.edu/ml/datasets/CalIt2+Building+People+Counts)
