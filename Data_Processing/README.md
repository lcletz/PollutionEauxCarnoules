# Folder "Data_Processing" description

This folder contains various .Rmd files that are needed to process Hydrosciences' and ADEME's databases.
Their data are inside .xls and .xlsm files that have then been manually converted to .csv and then processed under R programming.
Processing means keeping, renaming, organizing variables that have meanings and creating NAs-filled observations at any missing Dates.

Strict order to run those files:

 - tidy_datas.Rmd
 - COWG_tidy_datas.Rmd 
 - indicators_processing.Rmd
 - LD_table.Rmd
 - chr_to_num_processing.Rmd
 - dates_processing.Rmd
 - rainfall_datas_processing.Rmd
 
"weather_processing.Rmd" and "discharge_processing.Rmd" files are not part of the main process.

The next step is to impute missing data through "Data_Imputation" folder's "GAMMs_imputation_algo.Rmd".
