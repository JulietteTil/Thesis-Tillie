# Thesis-Tillie

This repository contains the code and notebooks used in the analysis and replication of results for my thesis. Below is a summary of the files and their purposes:

- **README.md**: the read-me file that contains a short explanation of the purpose of the code and functions as an introduction.
- **Base_Model_Schultz.ipynb**: this file replicates the results of Schultz and offers the possibility to play around with the settings. It additionally contains Bootstrap Aggregation of PCMCI.
- **Correctness_Statistic_Progress.ipynb**: this file contains the very first versions of the correctness statistic, including results for both the PCMCI and bagging estimators.  
  *Section 4.1.1*.
- **Correctness_Statistic_PCMCI.ipynb**: this file contains the correctness statistic, but solely for PCMCI. It also includes the simulations on random VAR coefficient matrices (instead of only the climate coefficient matrix, and the simulation graphs for different time series lengths.  
  *Section 4.1.1*.
- **Correctness_Statistic_Bagging.ipynb**: this file contains the correctness statistic, but solely for bagging. It also includes the simulations on random VAR coefficient matrices (instead of only the climate coefficient matrix, and the simulation graphs for different time series lengths.  
  *Section 4.1.1*.
- **Link_Strengthening.ipynb**: this file contains the tests regarding link strengthening and false positives of the tests, including the reported results and more.  
  *Section 4.2.1*.
- **Statistical_Tests.ipynb**: last but not least this file contains the estimates for the bias and corresponding bias plots, as well as the Chow test. It also includes some dataplots and additional results.  
  *Section 4.1.2 and Section 4.2.2*.

*Disclaimer*: Since some of these codes take a long time to run, it is always wise to check the purpose of the file and try and estimate the run time before running the entire file.
