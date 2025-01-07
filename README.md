

My Lord, here's a README for the project described in the document:

---

# Datascience Corona Statistics

**A comprehensive data science project analyzing the development of the COVID-19 pandemic using datasets provided by Statistik Austria.**  
**Authors:** Yasin Sahin and Sven Oberwalder  

## Table of Contents
- [Project Overview](#project-overview)
- [Datasets](#datasets)
- [Setup and Installation](#setup-and-installation)
- [Features](#features)
- [Usage](#usage)
- [Visualization](#visualization)
- [Results](#results)
- [License](#license)

---

## Project Overview
This project explores COVID-19-related statistics, focusing on vaccination, recovery, and demographic analysis. The data was cleaned, prepared, and visualized to uncover patterns and correlations.

## Datasets
- **Dataset 1**: Contains demographic details by political district.  
- **Dataset 2**: Includes economic and educational details by federal states.

**Source:**  
[Dataset 1](https://data.statistik.gv.at/web/meta.jsp?dataset=OGD_covidggstatus2_GGSTATUS_2)  
[Dataset 2](https://data.statistik.gv.at/web/meta.jsp?dataset=OGD_covidggstatus_GGSTATUS_1)  

## Setup and Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/Sormy23/DataScience_CoronaStatistics.git
   cd DataScience_CoronaStatistics
   ```
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Ensure datasets are in the `data` folder.

## Features
- **Data Cleaning**: Removed duplicates, handled null values, and mapped coded data to meaningful names.
- **Data Transformation**: Converted numerical, nominal, and normalized values for analysis.
- **Visualizations**:
  - Heatmaps
  - Pairplots
  - Boxplots and Violin Plots
  - Histograms and KDEs

## Usage
Run analysis scripts in `Datascience_CoronaStatistics.ipynb` for detailed visualizations.

## Visualization
Key graphs include:
- Correlation heatmaps to detect patterns.
- Bar charts and boxplots analyzing vaccination rates by demographics.
- KDE plots for density estimations.

## Results
- Correlation between education and vaccination rates was identified.
- Economic status strongly influences vaccination likelihood.
- Age and vaccination patterns suggest demographic-specific trends.

## License
This project is licensed under the MIT License.  
