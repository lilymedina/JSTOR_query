# JSTOR_query

This repository contains: 

## Main Files
1. `Summary.Rmd`: An `Rmd` file that summarizes the data on balance tests in papers, and its respective output documents: `Summary.pdf` and `Summary.html`
2. `sample/Balance_Tests.csv`: The data on balance tests in papers.

# Prepping files
3. An `Rmd` file (`create_data.Rmd`) that takes files `APSR.csv`, `JOP.csv` and `AJPS.csv` located in `\data` and outputs file `sample.csv also in `\data`.
4. Files `APSR.csv`, `JOP.csv` and `AJPS.csv` obtained from JSTOR using https://constellate.org/dataset/dashboard. The query reads: 
   
   "field experiment" OR 
   "field experiments" OR 
   "randomized experiment" OR
   "randomized experiments" OR 
   "randomized control trial" OR 
   "randomized control trials" OR 
   "Natural Experiment" OR
   "Natural Experiments"  OR 
   "Regression Discontinuity"
   
5. Output file `\data\sample.csv`. This file has stratified sample drawn from the combined datasets of the files mentioned above.

6. Output file `\data\new_sample.csv`. A randomly sorted dataset with the papers retreived from JSTOR that were not in `\data\sample.csv`.


   
