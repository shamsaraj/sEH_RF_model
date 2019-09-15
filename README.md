sEH_RF_model                                                                   
A tool for performing activity prediction against sEH (soluble Epoxide Hydrolase)
v. 1.0                                                                   
Copyright (C) 2019  Jamal Shamsara                                       
e-mail: shamsaraj@mums.ac.ir; jshamsara@yahoo.com
Usage of sEH_RF_model is free without any limitations.
There is NO warranty
https://github.com/shamsaraj
http://www.pharm-sbg.com
Usage example: sEH_RF_model -c [54, 76] -n sample_test_compounds.csv -d D:/sEH
Use -c and define a new list for local interpretation or -c True for a default list
The list should be defined a compound index list for local interpretation
To get indexes use ----Descriptor table for the Train---- work sheet of the supplementary file
Use -n and define a csv file for prediction
Use -d and define the sEH_RF_model.exe directory, use: slash instead of backslash,  path should be without space, current selection --> ', options.d

Example: sEH_RF_model -c [54, 76]" -n sample.csv -d D:/sEH_RF_model
