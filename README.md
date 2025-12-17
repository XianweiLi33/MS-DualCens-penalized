# Introduction
This repository contains R code to implement the methodology described in the paper:

**Li, X., Cook, R. J., & Diao, L. (2026+).**  
Variable Selection for Illness-death Processes under Dual Observation Schemes,
**Statistics in Medicine**

## helper_functions
This file contains several helper functions, including:
1. Calculation of the transition probability matrix
2. Computation of conditional expectations for the E-step in the EM algorithm
3. Computation of the observed data log-likelihood
   
## data_generation
This file contains functions to generate sample progressive multistate data for simulation purposes. It includes functions to create:

1. Complete data generated from an ilness-death model under continuous observation
3. Observed data under a dual censoring scheme

## EM
This file contains the code for the EM algorithm.

## example
This file contains the algorithm's implementation for a specific scenario. It serves as an example of how to apply the algorithm to multistate data under intermittent observation.
