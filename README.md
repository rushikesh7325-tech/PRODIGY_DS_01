# PRODIGY_DS_01
Task 1: Population Data Visualization


## Task Description
Analyze and visualize the distribution and trends of global population data from the World Bank dataset.

## Dataset
- **Source**: World Bank Population Data
- **Records**: [Your actual number] data points across [X] countries
- **Time Period**: 1960-2022
- **Features**: Country Name, Country Code, Year, Population

## Tools Used
- Python 3.9+
- Pandas for data manipulation
- Matplotlib & Seaborn for visualization
- Jupyter Notebook for development

## Methodology
1. **Data Loading**: Imported World Bank CSV dataset
2. **Data Reshaping**: Converted wide format to long format for analysis
3. **Data Cleaning**: Handled missing values and type conversions
4. **Visualization**: Created multiple chart types:
   - Line charts for temporal trends
   - Bar charts for country comparisons
   - Histograms for distribution analysis
5. **Statistical Analysis**: Calculated growth rates and summary statistics

## Key Findings
- Global population grew from [X] billion in 1960 to [Y] billion in 2022 (Z% increase)
- Top 3 most populous countries (2022): [List them]
- Average annual population growth rate: [Calculate it]%
- Population distribution is highly skewed, with most countries having <100M population

## Visualizations Created
1. `global_population_trend.png` - Worldwide population growth over time
2. `top10_countries.png` - Most populous countries comparison
3. `population_distribution.png` - Distribution histogram
4. `country_comparison.png` - Multi-country trend comparison

## Files in Repository
- `task01_analysis.ipynb`: Complete analysis notebook with code and outputs
- `API_SP.POP.TOTL_DS2_en_csv_v2.csv`: Original dataset
- `*.png`: All visualization outputs
- `README.md`: This documentation

## How to Run
```bash
# Clone repository
git clone https://github.com/rushikesh7325-tech/PRODIGY_DS_01
cd PRODIGY_DS_01

# Install dependencies
pip install pandas matplotlib seaborn jupyter numpy

# Launch Jupyter Notebook
jupyter notebook task01_analysis.ipynb
