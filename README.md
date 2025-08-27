# ATP Performance Dashboard

This project explores ATP tennis data to generate insights into player performance using **SAS** for analysis and **Power BI** for visualization.
There were three Null Hypotheses to be tested
## Hypothesis 1:
### - Players heights have no impact the number of aces achieved

## Hypothesis 2:
### - Match length does not differ across different tournaments

## Hypothesis 3:
### - Player handedness does not impact number of aces achieved

## Repository Contents
- **/docs** – Project write-up
- **/code** – SAS analysis code (This is saved in a word doc to be copied into SAS code)
- **/dashboard** – Power BI dashboard
- **/data** – Kaggle dataset

## Dataset
- **Source:** [ATP Tennis Dataset on Kaggle](https://www.kaggle.com/datasets/guillemservera/tennis)  
- **License/Terms:** Public dataset hosted on Kaggle  
- **How obtained:** Downloaded on 02/07/2025

## How to Run
- Once the required datasets have been downloaded (In this case, data from 2014-2024), append data together (No cleansing required at this stage, but do confirm datasets match each other).
- Import the data into SAS
- Run the SAS code highlighted in the SAS folder. 
- Consolidation of datasets was carried out in Excel but this can be done in SAS too (not in the code provided)

## Write Up
- The write up for this project can be found here:
[ATP_Write_Up.docx](Docs/ATP_Write_Up.docx)
 
## SAS
- The SAS code used to cleanse, transform, and analyse the data can be found here:
[code.docx](code/code.docx)

## Power BI
- The Power BI Dashboard is available here:
[ATP_PBI_Final.pbix](Dashboard/ATP_PBI.pbix)

## Results / Highlights
### Hypothesis 1 - Players heights have no impact the number of aces achieved
### REJECT THE NULL
(r=0.486, p < 0.0001)

### Hypothesis 2 - Match length does not differ across different tournaments
### REJECT THE NULL
(F=3.23, p < 0.0001)

### Hypothesis 3 - Player handedness does not impact number of aces achieved 
### REJECT THE NULL
(p = 0.0009)

## Conclusion
These finding can be used by players or coaches to help the way they train.
The data is rich enough to be improved endlessly and there are countless tools that could be implemented to help with cleansing, analysing or displaying the finding. 
