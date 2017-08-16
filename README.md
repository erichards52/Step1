# SRA Database Characterization, Viral Sequence Sensitivity Classifier Benchmarking & Virome Assembly

**Each of the sections below details the contents of each directory and its sub-directories**


-------------------------------------------------


## Step One: SRA Database Characterization (stepOne_SRAChar)
* Scripts for retrieving metadata for all datasets on the SRA
* Scripts for generating figures & tables using metadata downloaded from the SRA


-------------------------------------------------


## Step Two: Viral Sequence Sensitivity Classifier Benchmarking (stepTwo_Benchmark)
* Scripts for creating databases and performing classification (CLARK, CLARK-S, Kraken & Kaiju)
* Abundance tables generated by each classifier
* Scripts for building classifier benchmarking results
* Tables detailing each classifier's results
* Scripts used to download benchmark samples from the sequence read archive (SRA)


-------------------------------------------------


## Step Three: Virome Assembly (stepThree_Virome)
* Individual script for downloading datasets, performing classification using Kaiju, generating krona plots and automatically uploading to Git
* Abundance tables for each of the 1140 classifications conducted
* TSV files listing overall results of all classifications
* Scripts for selecting samples/classifications of interest
* Scripts for copying samples of interest to desired directories
* Scripts for building PCA plots from selected samples
