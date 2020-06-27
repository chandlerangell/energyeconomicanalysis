# Energy Storage Economic Analysis

## Project Overview 

This project seeks to help businesses and investors identify country-level markets that could be pursued for thermal energy storage (TES) projects.  Traditionally, market analyses like these are conducted by evaluating several key indicators for each market and then making a subjective assessment on which markets to invest in.  This project reduces subjectivity in market analyses by using a weighted scoring system.  Once investors and businesses agree on the most important market indicators, this scoring system will identify countries that should be further assessed for TES investment.  The key attribute of this scoring system is that it is repeatable and deterministic- as market statistics change over time, the system can be rerun using the preselected market indicators.

The World Bank’s International Finance Corporation (IFC) is looking for commercial opportunities in developing countries to support deployments of renewable energy and, specifically, thermal energy storage.   Institutions like the IFC along with businesses and investors around the world should have a platform that simplifies the process of evaluating and identifying potentially promising markets.

## Medium Blog Post

https://medium.com/@chandlerangell/identifying-investment-opportunities-for-thermal-energy-storage-da10f7530c9d

## Required Libraries
- Numpy
- Pandas
- Pycountry
- Plotly

## Project Files
- Raw Data (folder): contains all data from online sources in Excel format
- Energy Economic Analysis - ETL.ipynb: Performs the ETL data pipeline on all datasets located in the Raw Data folder
- Energy Economic Analysis - Analyze.ipynb: Analyzes the consolidated dataset and provides visualizations of it
- Energy Economic Analysis - Scoring Model.ipynb: Scores countries using a weighted scoring method
- ALL DATA.xlsx: Contains all data from all sources, is an output from the ETL notebook
- Dataset Indicators.xlsx: Contains the abbreviated and full name of the indicators being used
- Scored Countries.xlsx: Contains all scored country results 
- Weight Table.xlsx: User defined weights for the scoring model
- Energy Economic Analysis - Report.docx: project writeup


## Summary of Results

The scoring model created in this project adequately assessed global markets for their viability of TES investments.  Factors such as the regulatory environment, market potential for TES, and the state of the country’s electric grid were the salient indicators used in the scoring model.  The results from the scoring model were logical and interpretable using the weighting criteria that was established.  This indicates that it is possible to use this scoring model as an automated and more objective filtering mechanism for identifying countries to invest in.  With this scoring model, several tens of hours of analysts’ time can be saved and faster investment decisions can be reached by management. 

## Acknowledgements
Special thank you to the World Bank International Finance Corporation for helping to identify data sources and providing clarity on the problem being addressed in this project.
