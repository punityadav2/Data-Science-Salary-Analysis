# Data Science Salary Analysis Project

## 📊 Project Overview

This project provides a comprehensive exploratory data analysis (EDA) of data science job salaries across different countries, experience levels, and employment types. The analysis aims to uncover insights about salary trends, job market dynamics, and factors influencing compensation in the data science field.

## 📁 Dataset Information

**Dataset Source:** [Kaggle - Data Science Salaries 2023](https://www.kaggle.com/datasets/arnabchaki/data-science-salaries-2023)

### Dataset Description

The dataset contains **3,755 entries** with **11 columns**:

| Column | Description |
|--------|-------------|
| `work_year` | The year the salary was paid |
| `experience_level` | Experience level in the job (EN: Entry-Level, MI: Mid-Level, SE: Senior-Level, EX: Executive-Level) |
| `employment_type` | Type of employment (FT: Full-Time, PT: Part-Time, FL: Freelance, CT: Contract) |
| `job_title` | Role worked during the year |
| `salary` | Total gross salary amount paid |
| `salary_currency` | Currency of the salary (ISO 4217 code) |
| `salary_in_usd` | Salary converted to USD |
| `employee_residence` | Employee's primary country of residence (ISO 3166 code) |
| `remote_ratio` | Amount of work done remotely (0: On-Site, 50: Hybrid, 100: Remote) |
| `company_location` | Country of employer's main office (ISO 3166 code) |
| `company_size` | Median number of employees (S: Small, M: Medium, L: Large) |

### Key Statistics

- **Total Records:** 3,755
- **Years Covered:** 2020-2023
- **Unique Job Titles:** 93
- **Countries Represented:** 78 (employee residence), 72 (company locations)
- **Salary Range:** $5,132 - $450,000 USD
- **Average Salary:** $137,570 USD
- **Median Salary:** $135,000 USD

## 🔍 Analysis Highlights

### 1. **Data Quality**
- ✅ No missing values
- ⚠️ 1,171 duplicate entries identified
- 📊 Comprehensive coverage across multiple dimensions

### 2. **Key Findings**

#### Experience Level Distribution
- **Senior-Level (SE):** 2,516 positions (67%)
- **Mid-Level (MI):** Most common entry point
- **Entry-Level (EN):** Limited representation
- **Executive-Level (EX):** Smallest segment

#### Employment Type
- **Full-Time (FT):** 3,718 positions (99%)
- Other employment types (PT, FL, CT) are minimal

#### Top Job Titles
1. **Data Engineer:** 1,040 positions
2. **Data Scientist:** Second most common
3. **Data Analyst:** Third most common

#### Geographic Insights
- **United States:** Dominates with 3,004 employees (80%)
- **Salary Currency:** USD is most common (3,224 entries)
- **Company Size:** Medium-sized companies (M) employ the most (3,153)

#### Remote Work Trends
- **Average Remote Ratio:** 46.27%
- Distribution across On-Site (0), Hybrid (50), and Remote (100) work arrangements

### 3. **Salary Analysis**

#### Salary Statistics (USD)
- **Mean:** $137,570
- **Median:** $135,000
- **25th Percentile:** $95,000
- **75th Percentile:** $175,000
- **Maximum:** $450,000

#### Salary Trends
- Analyzed by experience level
- Compared across different work years (2020-2023)
- Evaluated by employment type and company size

## 📈 Visualizations

The notebook includes comprehensive visualizations:

1. **Top 10 Jobs by Work Year** - Trending job titles over time
2. **Top 3 Jobs by Experience Level** - Career progression insights
3. **Employment Type Distribution** - Work arrangement patterns
4. **Salary Distributions** - Box plots and histograms
5. **Average Salaries** - By various dimensions
6. **Remote Ratio Analysis** - Work location preferences
7. **Geographic Distribution** - Top 10 countries with most employees

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical computations
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical data visualization

## 📂 Project Structure

```
04. Data Science Salary/
│
├── Data_Science_Salary-EDA.ipynb    # Main analysis notebook
├── ds_salaries.csv                   # Dataset
└── README.md                         # Project documentation
```

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy matplotlib seaborn
```

### Running the Analysis

1. Clone or download this repository
2. Ensure the dataset (`ds_salaries.csv`) is in the same directory
3. Open `Data_Science_Salary-EDA.ipynb` in Jupyter Notebook or JupyterLab
4. Run all cells to reproduce the analysis

## 📊 Key Insights for Job Seekers

1. **Experience Matters:** Senior-level positions dominate the market
2. **Location Impact:** US-based positions offer competitive salaries
3. **Full-Time Preference:** Vast majority of positions are full-time
4. **Remote Flexibility:** Significant portion of roles offer remote work options
5. **Company Size:** Medium-sized companies are the largest employers

## 📊 Key Insights for Employers

1. **Competitive Landscape:** Understand market salary benchmarks
2. **Remote Work:** Flexibility is increasingly important
3. **Experience Distribution:** Senior talent is in high demand
4. **Geographic Trends:** US market dominates but international opportunities exist

## 🔮 Future Work

Potential extensions to this analysis:

- [ ] Predictive modeling for salary estimation
- [ ] Time series analysis of salary trends
- [ ] Correlation analysis between variables
- [ ] Machine learning model to predict salaries based on features
- [ ] Interactive dashboard for data exploration
- [ ] Comparison with other tech industry salaries

## 📝 Methodology

The analysis follows a structured approach:

1. **Data Loading & Inspection** - Understanding the dataset structure
2. **Data Cleaning** - Handling duplicates and data quality issues
3. **Feature Engineering** - Converting abbreviations to full forms for clarity
4. **Exploratory Data Analysis** - Statistical summaries and distributions
5. **Visualization** - Creating insightful charts and graphs
6. **Insights Extraction** - Drawing conclusions from the data

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Report bugs or issues
- Suggest new analyses or visualizations
- Improve documentation
- Add new features

## 📄 License

This project is available for educational and research purposes.

## 👨‍💻 Author

Created as part of a Machine Learning project portfolio.

## 🙏 Acknowledgments

- Dataset provided by [Arnab Chaki on Kaggle](https://www.kaggle.com/datasets/arnabchaki/data-science-salaries-2023)
- Inspired by the data science community's interest in salary transparency

---

**Note:** This analysis is based on publicly available data and should be used as a general guide. Actual salaries may vary based on numerous factors including specific skills, company culture, negotiation, and market conditions.

