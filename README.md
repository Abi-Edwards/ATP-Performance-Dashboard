## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [How to Run](#how-to-run)
- [Results](#results)

# ATP Performance Dashboard
## Project-overview
This project investigated the question “What measurable factors contribute to success among ATP (Association of Tennis Professionals) tournament champions spanning 2014 to mid-2024”. The datasets, which were sourced from Kaggle, were manually compiled and appended to each other in Excel, before being imported into SAS for cleaning and analysis, and Power Bi for visualisation.
This project centres around three null hypotheses: 

### Hypothesis 1:
#### - Players heights have no impact the number of aces achieved

### Hypothesis 2:
#### - Match length does not differ across different tournaments

### Hypothesis 3:
#### - Player handedness does not impact number of aces achieved

## Tools used
![Excel](https://img.shields.io/badge/Excel-Analysis-green)
![SAS](https://img.shields.io/badge/SAS-Analysis-blue)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-orange)

## Dataset
- **Source:** [ATP Tennis Dataset on Kaggle](https://www.kaggle.com/datasets/guillemservera/tennis)  
- **License/Terms:** Public dataset hosted on Kaggle  
- **How obtained:** Downloaded on 02/07/2025

## How to Run
- Find the data at https://www.kaggle.com/datasets/guillemservera/tenni
- Download required datasets (In this case data from 2014 to 2024 was used)
- Open the files in excel and ensuring the datasets match each other, copy and paste into one "master sheet"
- Open SAS Enterprise Guide
- Import the master sheet
- Run the code found here [code.docx](code/code.docx)
- Export the "Results" outputs and save in Excel
- Visuals can now be created using your tool of choice - I chose Power BI and my dashboard can be found here [ATP_PBI_Final.pbix](Dashboard/ATP_PBI.pbix)

## Write Up
- The write up for this project can be found here:
[ATP_Write_Up.docx](Docs/ATP_Write_Up.docx)
 
## SAS
- The SAS code used to cleanse, transform, and analyse the data can be found here:
[code.docx](code/code.docx)

## Power BI
- The Power BI Dashboard is available here:
[ATP_PBI_Final.pbix](Dashboard/ATP_PBI.pbix)

## Results
### Hypothesis 1 - Players heights have no impact the number of aces achieved
### Test - Pearson Correlation 
### Conclusion - REJECT THE NULL
(r=0.486, p < 0.0001)

### Hypothesis 2 - Match length does not differ across different tournaments
### Test - One-Way ANOVA
### Conclusion - REJECT THE NULL
(F=3.23, p < 0.0001)

### Hypothesis 3 - Player handedness does not impact number of aces achieved 
### Test - Independent T-Test
### Conclusion - REJECT THE NULL
(p = 0.0009)

## Conclusion
Overall, the findings highlight how statistical methods can uncover meaningful trends in sports data. These insights could inform coaching strategies, player development, and tournaments planning. The project also demonstrates the importance of careful data preparation and the use of appropriate tools to support analysis. 
