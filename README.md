# ESG Score Impact Analysis for Portfolio Optimization

## Overview

This project investigates how ESG (Environmental, Social, and Governance) scores influence financial risks and returns. It aims to assist investors in understanding the potential impact of ESG ratings on performance.

## Project Structure

### 1. Data Acquisition and Preparation
- ESG scores were merged with financial return data sourced across different sectors and timeframes.
- The data was cleaned to remove nulls and ensure consistent formatting. ESG components (E, S, and G) were standardized for comparison.

### 2. Exploratory Data Analysis (EDA)
- A pair plot and heatmaps were created to explore linear and non-linear relationships among ESG scores and financial metrics.
- Sector-wise analysis showed how ESG compliance varies across industries.

### 3. Feature Engineering and Transformation
- Composite ESG scores were derived from individual E, S, G scores for simplification.
- Log transformations were applied to returns data to handle skewness and outliers.

### 4. Modeling and Interpretation
- Linear regression was used to model the impact of ESG scores on stock returns and risk.
- Coefficients were interpreted to understand the magnitude and direction of ESG influence on financial outcomes.
  
### 5. Data Visualization
- Designed an interactive [Power BI dashboard](https://github.com/user-attachments/assets/17fbee0e-5de5-4549-9cc3-83b3af2c16e4) to showcase:
    - High ESG score sectors (e.g., Healthcare, Tech)
    - Best performing industries by return and risk
    - ESG–Return–Risk correlations across companies and Filterable views by industry for 
      executive summaries

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- SciPy
- Seaborn
- Scikit-learn
- Linear Regression
- Power BI

## Output

- The final model achieved 76% overall accuracy.
- It performed especially well for retained customers with 91% precision, and identified churners with 65% recall, offering a useful foundation for retention strategies.
  
  ![image](https://github.com/user-attachments/assets/17fbee0e-5de5-4549-9cc3-83b3af2c16e4)


## How to Use

- ### Clone this repository:
  ```bash
  git clone [https://github.com/Bhuvi1901/ESGImpactAnalysisRepository](https://github.com/Bhuvi1901/ESGImpactAnalysisRepository)
  ```
- ### Navigate to the project folder:
  ```bash
  cd ESGImpactAnalysisRepository
  ```
- ### Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
- ### Run the Jupyter Notebook to execute the workflow.

## Future Improvements

- Include granular ESG sub-metrics like emissions or diversity scores.
- Experiment with nonlinear models and deploy a real-time dashboard.
