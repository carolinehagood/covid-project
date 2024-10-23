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
   - clean_vaccine_data.csv
   - COVID-19_Death_Counts.csv
   - Covid_deaths_cleaned.csv
   - Total_cleaned_data.csv
   - us-daily-covid-vaccine-doses-administered.csv

2. Scripts
   - Cleaning_Covid_Death_Data.ipynb
   - Combining_data.ipynb
   - Final_Data_Analysis.ipynb
   - vaccine_data_cleaning.ipynb
   - MasterScript.ipynb
     
3. Output
   - output/Covid-Deaths-Year-Comp.png
   - output/Covid-Deaths21.png
   - output/Covid-Deaths22.png
   - output/Covid-Weekly-Dist.png
   - output/Vaccine-Weekly-Dist.png
   - output/Vaccine-Year-Comp.png
   


## Reproducing Results

- Fork this repository, and clone forked repository in terminal of workspace

  ```! git clone https://github.com/carolinehagood/covid-project.git```

- Install and load packages and all dependencies

  ```pip install -r requirements.txt ```
  
- Read in COVID-19_Death_Counts.csv and us-daily-covid-vaccine-doses-administered.csv datasets to be cleaned. Run Cleaning_Covid_Death_Data.ipynb and vaccine_data_cleaning.ipynb
  
- Run Combining_data.ipynb script to join vaccine and covid-19 datasets
  
- Finally, run the Final_Data_Analysis.ipynb 


## References

