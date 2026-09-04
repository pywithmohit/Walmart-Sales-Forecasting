# Walmart Sales Forecasting

A Python and Jupyter notebook for cleaning, combining, and exploring Walmart weekly sales data. The current notebook prepares the merged dataset and visualizes total sales over time as a foundation for forecasting work.

## What the notebook does

1. Imports `pandas`, `numpy`, and `pathlib`.
2. Loads the features, stores, test, and training CSV files.
3. Prints the shape of each loaded dataset.
4. Displays the features dataset schema with `features.info()`.
5. Converts the `Date` columns to pandas datetime values.
6. Fills missing markdown, CPI, and unemployment values in the features data.
7. Merges store and feature data with the training sales data.
8. Compares holiday and non-holiday sales and summarizes sales by store type.
9. Aggregates weekly sales by date and saves the trend chart to `weekly sales trend.png`.

The notebook currently focuses on data preparation and exploratory data analysis. A forecasting model has not yet been added.

## Sales trend

![Total weekly sales over time](weekly%20sales%20trend.png)

## Files

- `Notebook.ipynb`: notebook containing the data-loading and transformation code
- `weekly sales trend.png`: generated chart of total weekly sales over time
- `features.csv`: feature data, including the `Date` column
- `stores.csv`: store data
- `test.csv`: test data
- `train.csv`: training data

## Requirements

- Python 3.9 or newer
- pandas
- numpy
- Jupyter, or VS Code with the Jupyter extension

Install the dependencies:

```bash
python -m pip install pandas numpy jupyter
```

## Run the notebook

1. Open `Notebook.ipynb` in Jupyter or VS Code.
2. Select a Python environment with the required packages.
3. Run the cells from top to bottom.

The loader looks for CSV files inside `Data/` first. If that directory is not present, it loads the files from the repository root.

## Data layout

For the local project layout, place the CSV files in a `Data/` directory:

```text
Data/
├── features.csv
├── stores.csv
├── test.csv
└── train.csv
```