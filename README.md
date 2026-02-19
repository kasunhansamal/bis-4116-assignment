# HR Analytics: Job Change of Data Scientists

This repository contains a comprehensive data analysis of factors that lead data scientists to look for a job change. The goal is to identify key predictors of employee turnover using the "HR Analytics: Job Change of Data Scientists" dataset.

## Project Structure

- `REPORT.md`: The detailed analysis report, including findings, visualizations, and recommendations.
- `analysis.ipynb`: A Jupyter Notebook containing the Python code used for data loading, cleaning, and analysis.
- `aug_train.csv`: The dataset used for the analysis (sourced from Kaggle).
- `images/`: Directory containing the generated plots used in the report.

## Getting Started

### Prerequisites
To run the analysis code, you will need Python installed with the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- kagglehub

You can install them via pip:
```bash
pip install pandas numpy matplotlib seaborn kagglehub
```

### Running the Analysis
1.  Clone this repository.
2.  Open `analysis.ipynb` in Jupyter Notebook or JupyterLab.
3.  Run all cells to download the dataset and generate the analysis.

## Key Findings
- **Attrition Rate:** ~16.6% (in cleaned subset)
- **Top Driver:** City Development Index (CDI) is the strongest predictor. Lower CDI correlates with higher intent to change jobs.

