# Comparing Economic Performance Across China, the United States, and the United Kingdom Using Python

A Python-based macroeconomic comparison project using World Bank data from 2014 to 2023.

## Product Links
- GitHub repository: https://github.com/3545935202-sketch/acc102-worldbank-economic-comparison
- Demo video (Mediasite): https://video.xjtlu.edu.cn/Mediasite/Play/a7679f9ce36d4a0ab83b05d5803681721d

## 1. Problem and Intended User
This project examines how economic performance can be compared more meaningfully across countries using multiple indicators rather than GDP growth alone.

The intended users are economics students, finance students, and general users who want a simple and visual comparison of macroeconomic trends.

## 2. Data
Source: World Bank  
Access date: 22 April 2026  

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
The project uses Python with pandas and matplotlib to:
- load and inspect the dataset
- check missing values
- reshape the data from wide format to long format using `melt`
- extract year values and convert indicator values into numeric form
- reorganise the data into a country-year comparison table using `pivot_table`
- rename variables for readability
- calculate simple comparisons using `groupby`
- visualise trends using line charts

## 4. Key Findings
- China showed the strongest average GDP growth over the selected period.
- Inflation was more volatile in the United States and the United Kingdom, especially after 2020.
- Unemployment patterns differed across the three countries.
- The project shows that economic performance should be evaluated through multiple indicators rather than GDP growth alone.

## 5. Repository Structure
- `worldbank_economic_comparison.ipynb` – main notebook
- `worldbank_data.csv` – dataset used in the analysis
- `requirements.txt` – required Python libraries
- `figures/` – exported charts

## 6. How to Run
1. Download or clone this repository.
2. Keep `worldbank_data.csv` in the same folder as the notebook.
3. Open `worldbank_economic_comparison.ipynb` in Jupyter Notebook or JupyterLab.
4. Run the notebook from top to bottom.

Required libraries:
- pandas
- numpy
- matplotlib

## 7. Limitations and Possible Improvements
This project only includes three countries and three indicators, so it cannot fully represent the global economy. The analysis is descriptive rather than causal, and other relevant variables such as trade, exchange rates, or public debt are not included.

Possible improvements:
- add more countries
- add more macroeconomic indicators
- extend the time period
- build an interactive dashboard version

## 8. Author
Rose Guo  
ACC102 Mini Assignment
