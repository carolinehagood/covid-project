## Project Name and Introduction 
COVID-19 DEATHS DECREASE OVERTIME AS VACCINATION DOSES INCREASE: A TIME SERIES ANALYSIS
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
   - scripts/Cleaning_vaccine_data.ipynb
   - scripts/Combining_data.ipynb
   - scripts/Final_Data_Analysis.ipynb
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
  
- Read in COVID-19_Death_Counts.csv and Vaccination-data-CDC.csv datasets to be cleaned. Run Cleaning_Covid_Death_Data.ipynb and vaccine_data_cleaning.ipynb
  
- Run Combining_data.ipynb script to join vaccine and covid-19 datasets
  
- Finally, run the Final_Data_Analysis.ipynb 


## References

[1] “Chapter 4: Granger Causality Test — Time Series Analysis Handbook,” phdinds-aim.github.io. https://phdinds-aim.github.io/time_series_handbook/04_GrangerCausality/04_GrangerCausality.html


[2] F. Chirico, J. Teixeira da Silva, P. Tsigaris, and K. Sharun, “Safety & Effectiveness of COVID-19 vaccines: a Narrative Review,” Indian Journal of Medical Research, vol. 155, no. 1, p. 91, 2022, doi: https://doi.org/10.4103/ijmr.ijmr_474_21. 


[3] “8.2 Cross Correlation Functions and Lagged Regressions | STAT 510,” PennState: Statistics Online Courses. https://online.stat.psu.edu/stat510/lesson/8/8.2


[4] “COVID-19 Vaccination Trends in the United States,National and Jurisdictional | Data | Centers for Disease Control and Prevention,” data.cdc.gov. https://data.cdc.gov/Vaccinations/COVID-19-Vaccination-Trends-in-the-United-States-N/rh2h-3yt2/about_data


[5] “Provisional COVID-19 Death Counts by Week Ending Date and State | Data | Centers for Disease Control and Prevention,” data.cdc.gov. https://data.cdc.gov/NCHS/Provisional-COVID-19-Death-Counts-by-Week-Ending-D/r8kw-7aab/about_data
‌
