# Comparing Economic Performance Across China, the United States, and the United Kingdom Using Python

## Product Link
- Track 2 repository: [add your GitHub repository link here]
- Demo video: [add your Mediasite video link here]

## 1. Problem & User
This project compares economic performance across China, the United States, and the United Kingdom from 2014 to 2023.  
The target users are economics students, finance students, and general users who want a simple and clear comparison of macroeconomic trends.

## 2. Data
The dataset was downloaded from the World Bank on 2026-04-22.

Selected countries:
- China
- United States
- United Kingdom

Indicators used:
- GDP growth (annual %)
- Inflation, consumer prices (annual %)
- Unemployment, total (% of total labor force) (modeled ILO estimate)

Main data file:
- `worldbank_data.csv`

## 3. Methods
This project uses Python for a basic but coherent analytical workflow.

Main steps:
- load the World Bank dataset using pandas
- inspect the data structure and missing values
- reshape the data from wide format to long format using `melt`
- convert year and value columns into analysis-friendly format
- reorganise the data into a cleaner comparison table using `pivot_table`
- rename variables for readability
- calculate country-level averages for GDP growth, inflation, and unemployment
- visualise the three indicators over time using line charts

## 4. Key Findings
- China showed the strongest average GDP growth over the selected period.
- Inflation appeared more volatile in the United States and the United Kingdom, especially in recent years.
- Unemployment levels differed across the three countries, reflecting different labour market conditions and economic structures.
- The comparison suggests that economic performance should be evaluated using multiple indicators rather than GDP growth alone.

## 5. How to Run
1. Download or clone this repository.
2. Make sure `worldbank_data.csv` is in the same folder as the notebook.
3. Open `worldbank_economic_comparison.ipynb` in Jupyter Notebook or JupyterLab.
4. Run all cells from top to bottom.

Required packages:
- pandas
- numpy
- matplotlib

## 6. Repository Structure
- `worldbank_economic_comparison.ipynb` – main notebook
- `worldbank_data.csv` – dataset used in the analysis
- `requirements.txt` – required Python libraries
- `figures/` – optional exported chart images

## 7. Limitations & Next Steps
This project has several limitations. First, it only compares three countries, so the findings cannot represent the global economy. Second, only three macroeconomic indicators were used, so other important dimensions such as trade, public debt, and exchange rates were not included. Third, the analysis is descriptive and does not fully explain the structural or political reasons behind the observed differences.

Possible next steps:
- include more countries
- include more indicators
- add regional grouping or ranking features
- build an interactive version of the project using Streamlit

## 8. Author
Rose Guo  
ACC102 Mini Assignment

## 9. Note on AI Use
AI tools were used only to support planning, wording, and debugging. All code, results, and explanations were checked and understood before submission.
