sEH_RF_model                                                                   
A tool for performing activity prediction against sEH (soluble Epoxide Hydrolase)
v. 1.0                                                                   
Copyright (C) 2019  Jamal Shamsara                                       
e-mail: shamsaraj@mums.ac.ir; jshamsara@yahoo.com

Usage of sEH_RF_model is free without any limitations.
There is NO warranty
https://github.com/shamsaraj
http://www.pharm-sbg.com

Use -c and define a new list for local interpretation or -c True for a default list.
The list should be defined as compound index numbers (separated by comma, without space) for local interpretation.
To get indexes use ----Train set---- work sheet of the supplementary file.

Use -n and define a csv file for prediction or "" to not make any predictions

Use -d and define the sEH_RF_model.exe directory, use: slash instead of backslash,  path should not include any spaces

Usage example: sEH_RF_model -c 54,76 -n sample_test_compounds.csv -d D:/sEH_RF_model

Publication: https://www.eurekaselect.com/175739/article
