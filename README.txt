## Recreating My Analysis

1. Clone the (temporarily public) github repo located here:

https://github.com/RyanTWingate/ml1

2. Create a conda environment from the included environment.yml file:

* conda env create -f environment.yml

3. Source the datasets from the following locations:

* https://www.kaggle.com/c/titanic
* https://archive.ics.uci.edu/ml/datasets/Adult

4. Place that data into "raw_adult" and "raw_titanic" directories (note that
the raw data are also already there).

5. Clean these files using the files in the "cleaning scripts" directory,
specifically:

* adult_cleaning.ipynb
* titanic_cleaning.ipynb

6. The clean data will be placed into the directory, "clean".

7. Execute the scripts in "analyze.ipynb" to recreate all analysis used to
write the report.
