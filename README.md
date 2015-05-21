# Randomforest matlab Mac (RF_MexStandalone-v0.02.zip)
Source: https://code.google.com/p/randomforest-matlab/downloads/list

#What is it?
This repo contains the source code to use random forest in Matlab on Mac OS X 10.10.3. The source code has modified the modified files according to **Issue 64: Compilation Problems with Matlab 2014a on Mac** (https://code.google.com/p/randomforest-matlab/issues/detail?id=64).

You just need to run the next scripts
1. RF_Class_C/compile_class_mac.m
2. RF_Reg_C/compile_reg_mac.m

The source files that were modified are:
1. src/mex_regressionRF_train.cpp
2. src/mex_regressionRF_predict.cpp
3. src/mex_regressionRF_predict.cpp
4. src/mex_regressionRF_train.cpp

#Software:

1. Matlab 2014b
2. Xcode 6.3.2
3. gfortran 4.2.3 (http://code.obs.carnegiescience.edu/carnegie-python-distribution/downloads/gfortran-4.2.3.dmg/view)


