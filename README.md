# India Digital Payments & UPI Fraud Analysis

## Project Overview

This project explores India's digital payments ecosystem using UPI (Unified Payments Interface) transaction data and related RBI banking and fraud datasets. It applies Python-based data cleaning, data manipulation, exploratory data analysis (EDA), statistical summaries, and visualizations to understand transaction trends and patterns.

The project is designed as a hands-on data analytics practical, demonstrating core skills in Python, Pandas, NumPy, Matplotlib, and Excel data processing.

## Objectives

- Clean and prepare Excel datasets for analysis.
- Identify missing values and duplicate records.
- Analyze monthly UPI transaction volume and value.
- Calculate transaction growth and average ticket size.
- Visualize digital payment trends over time.
- Summarize important patterns using descriptive statistics.
- Explore related RBI banking and fraud data where appropriate.

## Dataset

**File:** `India_Digital_Payments_Data.xlsx`

The workbook contains multiple sheets covering UPI monthly statistics, financial-year summaries, and related RBI banking, area, and fraud information.

The `UPI_Monthly` sheet includes fields such as:

- `Month`
- `Fiscal Year`
- `Month No.`
- `Banks Live on UPI`
- `Volume (Mn)`
- `Value (Rs Cr)`
- `Avg Ticket Size (Rs)`
- `MoM Volume %`
- `YoY Volume %`
- `YoY Value %`
- `Note`

*Note: Dataset figures and their definitions should be verified against the original data source before drawing policy or financial conclusions.*

## Technologies Used

- **Python** — analysis and scripting
- **Pandas** — data cleaning and manipulation
- **NumPy** — numerical calculations
- **Matplotlib** — charts and visualizations
- **OpenPyXL** — Excel file processing
- **Jupyter Notebook** — interactive analysis

## Project Structure

```text
UPI-Fraud_Analysis/
├── data/
│   └── raw/
│       └── India_Digital_Payments_Data.xlsx
├── notebooks/
│   └── upi_fraud_analysis.ipynb
├── reports/
├── requirements.txt
└── README.md
```

The notebook and dataset filenames above are examples; update them to match the files you actually upload.

## Analysis Performed

### 1. Data Loading
Imported the monthly UPI dataset from Excel using Pandas.

### 2. Data Cleaning
- Standardized column names.
- Checked missing values.
- Removed duplicate records.
- Converted the month field to a date format.
- Sorted records chronologically.

### 3. Data Manipulation
- Selected relevant transaction columns.
- Filtered high-volume months.
- Calculated month-on-month transaction volume growth.
- Examined average transaction ticket size.

### 4. Exploratory Data Analysis
- Generated descriptive statistics.
- Compared transaction volume and value over time.
- Identified months with the highest and lowest transaction volumes.
- Examined relationships between numerical variables.

### 5. Visualization
Created time-series charts to communicate changes in UPI transaction volume and transaction value.

## Key Findings

The supplied workbook covers monthly UPI data from April 2016 through September 2026.

According to the workbook:
- September 2026 recorded a UPI transaction volume of approximately **24,068.38 million**.
- September 2026 recorded a transaction value of approximately **₹2,937,396.67 crore**.
- August 2026 had the highest monthly transaction volume in the supplied series.
- May 2026 had the highest monthly transaction value in the supplied series.

These findings are based on the workbook's contents and have not been independently verified against official publications.

## Installation and Usage

### Prerequisites
Install Python and Jupyter Notebook.

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
```

Replace the URL and repository name with your actual GitHub details.

### 2. Install dependencies

```bash
python -m pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook

```bash
jupyter notebook
```

### 4. Run the analysis

Open the notebook in the `notebooks/` folder and execute the cells from top to bottom.

Ensure the Excel dataset is available at the path used in the notebook. If you change the folder structure, update the file path accordingly.

## Limitations

- The analysis depends on the completeness and accuracy of the supplied workbook.
- Trends and correlations do not establish causation.
- UPI transaction growth alone does not measure fraud.
- RBI fraud datasets may use different reporting periods, definitions, and units from UPI transaction datasets; analyze and compare them only after aligning those definitions.

## Future Improvements

- Add more comprehensive data-quality checks.
- Build an interactive dashboard using Power BI or Plotly.
- Analyze RBI fraud indicators separately by bank group, area, and reporting period.
- Add documented tests for data-cleaning functions.
- Publish a dashboard or deploy the analysis as a web application.

## Learning Outcomes

This project demonstrates practical skills in data loading, data cleaning, transformation, exploratory analysis, descriptive statistics, visualization, and reproducible Python workflows.

## Author

**Your Name**

Data Analytics | Python | Exploratory Data Analysis

## Disclaimer

This project is intended for educational and analytical purposes. Findings should not be treated as official financial, regulatory, or fraud-risk conclusions without verification against the original sources.

