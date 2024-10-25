## Project Name and Introduction 
 Maggie Welch, Caroline Hagood, Emmanuella Cann


## Software and Platform

This project was developed using Python and includes key functionalities such as data cleaning, visualization, merging, cross-correlation function, pearson correlation, and granger causality. A range of python packages were used to achieve these tasks:

- pandas
- numpy
- matplotlib
- seaborn
- scipy
- statsmodels
  
## Documentation Map

LICENSE

This project is licensed under the MIT License - see the [LICENSE](https://github.com/carolinehagood/covid-project/blob/main/LICENSE) file for details.

1. Data
   - data/COVID-19_Death_Counts.csv
   - data/Covid_deaths_cleaned.csv
   - data/merged_data.csv
   - data/Vaccination-data-CDC.csv
   - data/vaccine_data_cleaned.csv


2. Scripts
   - scripts/Cleaning_Covid_Death_Data.ipynb
   - scripts/Combining_data.ipynb
   - scripts/Final_Data_Analysis.ipynb
   - scripts/vaccine_data_cleaning.ipynb
   - scripts/MasterScript.ipynb
  
     
3. Output
   - output/Covid Deaths 2020.png
   - output/Covid Deaths 2021.png
   - output/Covid Deaths 2022.png
   - output/Covid Deaths Line Graph.png
   - output/Cummulative vaccinations.png
   - output/Vaccines weekly overtime.png
  
   


## Reproducing Results

- Fork this repository, and clone forked repository in terminal of workspace

  ```! git clone https://github.com/carolinehagood/covid-project.git```

- Install and load packages and all dependencies

  ```pip install -r requirements.txt ```
  
- Read in COVID-19_Death_Counts.csv and us-daily-covid-vaccine-doses-administered.csv datasets to be cleaned. Run Cleaning_Covid_Death_Data.ipynb and vaccine_data_cleaning.ipynb
  
- Run Combining_data.ipynb script to join vaccine and covid-19 datasets
  
- Finally, run the Final_Data_Analysis.ipynb 


## References

