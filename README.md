# Walmart Sales Forecasting

A data science project focused on understanding and forecasting weekly sales for Walmart stores using a structured retail dataset. This repository includes a Jupyter notebook for exploratory data analysis (EDA), dataset preparation, and early modeling groundwork.

## Project Overview

The project uses the Walmart sales forecasting dataset to explore:

- sales trends over time
- holiday vs non-holiday sales behavior
- store-level performance by type and size
- missing value handling and feature preparation
- data merging and feature engineering basics for forecasting

This repository is designed as a practical baseline for a forecasting workflow and can be extended with regression, time series, or ensemble models.

## Dataset

The project uses the following files from the `Data/` directory:

- `features.csv`
- `stores.csv`
- `train.csv`
- `test.csv`

These data sources include store metadata, weekly sales records, and external features such as CPI, unemployment, and holiday flags.

## Repository Structure

```text
Walmart Sales Forecasting/
├── Data/
│   ├── features.csv
│   ├── stores.csv
│   ├── test.csv
│   └── train.csv
├── Notebook.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── .ipynb_checkpoints/
```

## Tech Stack

- Python 3.9+
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn

## Setup

1. Clone the repository:

```bash
git clone https://github.com/<your-username>/Walmart-Sales-Forecasting.git
cd Walmart-Sales-Forecasting
```

2. Create a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate
```

On Windows PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

## Run the Notebook

Open `Notebook.ipynb` in Jupyter or VS Code with the Jupyter extension and run the cells in order.

## Highlights from the Notebook

The notebook currently covers:

- loading datasets from `Data/`
- checking dataset shapes and null values
- converting date columns to datetime
- handling missing values in markdown and economic features
- merging train and feature data
- exploring holiday impact on sales
- analyzing sales trends over time
- evaluating store type sales patterns

## Project Goal

The main objective is to build a robust sales forecasting pipeline that can estimate weekly sales based on historical data and store-level features.

## Next Steps

Potential extensions for this project include:

- feature engineering for time series forecasting
- train/test validation splits
- regression models such as XGBoost, Random Forest, or Gradient Boosting
- evaluation using RMSE and MAE
- deployment or API-ready prediction scripts

## License

This project is for educational and research purposes. Add a license if you plan to publish it publicly.

## Author

This project is maintained as a personal data science portfolio project for Walmart sales analysis and forecasting.
