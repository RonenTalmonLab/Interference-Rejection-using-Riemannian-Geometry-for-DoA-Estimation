# Interference-Rejection-using-Riemannian-Geometry-for-DoA-Estimation

The code in this repository creates the figures presented in this article:
https://arxiv.org/pdf/2301.03399.pdf

The code is self contained and was tested using Matlab 2018b on Windows 10.

The main file is "LoopWrapper.m.". It calls all the other functions and scripts.
Inside LoopWrapper.m, in lines 20-26, there are flags controlling which figures to plot. 
Please note that only one of the flags should have a logical '1' value at a time. 

The code requires the RIR simulator to be installed.  
Please download it from:
https://www.audiolabs-erlangen.de/fau/professor/habets/software/rir-generator
