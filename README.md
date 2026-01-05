# PRODIGY_DS_01: World Population Data Visualization

## 📊 Project Overview
Comprehensive analysis and visualization of global population trends using World Bank dataset covering 64 years of demographic data (1960-2023).

**Internship:** Prodigy InfoTech - Data Science Intern  
**Task:** Task 1 - Population Distribution Analysis  
**Completion Date:** January 2026  
**Status:** ✅ Completed

---

## 🎯 Objective
Create data-driven visualizations to analyze:
- Global population growth trends over six decades
- Distribution patterns of population across countries
- Comparative growth analysis of major nations
- Statistical insights into demographic shifts

---

## 📁 Dataset Information
- **Source:** [World Bank Open Data](https://data.worldbank.org/indicator/SP.POP.TOTL)
- **Indicator:** SP.POP.TOTL (Total Population)
- **File:** `API_SP.POP.TOTL_DS2_en_csv_v2.csv`
- **Total Records:** 13,000+ data points
- **Countries Covered:** 200+ nations and territories
- **Time Period:** 1960-2023 (64 years)
- **Key Features:** Country Name, Country Code, Year, Population Count

---

## 🛠️ Technologies & Tools

### Programming & Libraries
- **Python:** 3.10.19
- **Pandas:** 2.3.3 - Data manipulation and cleaning
- **NumPy:** 2.2.5 - Numerical computing
- **Matplotlib:** 3.10.7 - Static visualizations
- **Seaborn:** 0.13.2 - Statistical graphics

### Development Environment
- **IDE:** Jupyter Notebook
- **Environment Manager:** Anaconda
- **Version Control:** Git & GitHub

---

## 📈 Methodology

### Phase 1: Data Acquisition & Loading
- Downloaded World Bank population dataset in CSV format
- Loaded data using Pandas with proper handling of metadata rows (`skiprows=4`)
- Initial exploration of dataset structure and dimensions

### Phase 2: Data Preprocessing
- **Reshaping:** Converted wide-format data to long-format using `pd.melt()`
- **Type Conversion:** Cast Year to integer and Population to float
- **Data Cleaning:** 
  - Removed rows with missing population values
  - Filtered out regional aggregates (World, continents, income groups)
  - Retained only country-level data
- **Output:** Clean dataset with ~13,000 rows ready for analysis

### Phase 3: Exploratory Data Analysis
- Grouped data by year to analyze global trends
- Identified top 10 most populous countries
- Calculated growth rates and percentage changes
- Analyzed population distribution patterns

### Phase 4: Data Visualization
Created four distinct visualization types:
1. **Time Series Line Chart:** Global population trajectory
2. **Horizontal Bar Chart:** Top 10 countries ranking
3. **Histogram:** Distribution of country populations
4. **Multi-line Comparison:** Growth trends of 5 major nations

---

## 🔍 Key Findings

### Global Demographics
- **World Population (1960):** ~3.0 billion
- **World Population (2023):** ~8.0 billion
- **Total Growth:** 160%+ increase over 63 years
- **Average Annual Growth:** ~79 million people/year
- **Trend:** Consistent upward trajectory with slight deceleration in recent decades

### Top 10 Most Populous Countries (2023)
1. **India** - 1.43 billion (17.8% of world)
2. **China** - 1.43 billion (17.8% of world)
3. **United States** - 340 million (4.2% of world)
4. **Indonesia** - 277 million (3.5% of world)
5. **Pakistan** - 240 million (3.0% of world)
6. **Nigeria** - 223 million (2.8% of world)
7. **Brazil** - 216 million (2.7% of world)
8. **Bangladesh** - 173 million (2.2% of world)
9. **Russia** - 144 million (1.8% of world)
10. **Mexico** - 128 million (1.6% of world)

### Distribution Insights
- **Concentration:** Top 10 countries represent 58% of global population
- **Skewness:** Distribution is highly right-skewed
- **Median vs Mean:** Median country population significantly lower than mean
- **Small Nations:** 50+ countries have populations under 10 million

### Growth Patterns
- **India** overtook China as most populous nation (~2023)
- **Asia** dominates with 60% of world population
- **Africa** shows highest growth rates in recent years
- **Developed nations** exhibit slower, stable growth
- **Developing nations** show rapid population expansion

---

## 📊 Visualizations

### 1. Global Population Trend (1960-2023)
![Global Population Trend](visualizations/global_population_trend.png)

**Insights:** Demonstrates exponential population growth from 3 billion to 8 billion, with growth rate gradually slowing in recent decades.

---

### 2. Top 10 Most Populous Countries
![Top 10 Countries](visualizations/top10_countries.png)

**Insights:** India and China dominate with nearly equal populations. Significant gap between top 2 and remaining countries.

---

### 3. Population Distribution Histogram
![Population Distribution](visualizations/population_distribution.png)

**Insights:** Most countries have small to medium populations (<100M). Large population countries are outliers.

---

### 4. Country-wise Growth Comparison
![Country Comparison](visualizations/country_comparison.png)

**Insights:** India shows steeper growth trajectory than China post-2000. USA maintains steady linear growth.


---

## 🚀 How to Run This Project

### Prerequisites
Ensure you have Python 3.8+ installed. Install required packages:

```bash
pip install pandas numpy matplotlib seaborn jupyter


# Step-by-Step Execution
# 1. Clone this repository
git clone https://github.com/rushikesh7325-tech/PRODIGY_DS_01.git

# 2. Navigate to project directory
cd PRODIGY_DS_01

# 3. Launch Jupyter Notebook
jupyter notebook

# 4. Open task01_analysis.ipynb

# 5. Run all cells
# Menu → Cell → Run All
# Or use Shift+Enter for each cell

