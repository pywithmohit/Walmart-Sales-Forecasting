# Walmart Sales Forecasting

An exploratory Walmart sales forecasting project built with Python and Jupyter. The notebook loads store, feature, training, and test data for analysis and model development.

## Project files

- `Notebook.ipynb`: data loading, transformation, and forecasting analysis
- `Data/features.csv`: weekly store features and external indicators
- `Data/stores.csv`: store metadata and store types
- `Data/train.csv`: historical weekly sales used for training
- `Data/test.csv`: dates and stores reserved for predictions

## Requirements

- Python 3.9 or newer
- pandas
- numpy
- Jupyter or VS Code with the Jupyter extension

Install the dependencies with:

```bash
python -m pip install pandas numpy jupyter
```

## Run the notebook

1. Open `Notebook.ipynb` in Jupyter or VS Code.
2. Select the project Python environment as the notebook kernel.
3. Run the cells from top to bottom.

The loader checks for a `Data/` directory first and falls back to the repository root, so the notebook works with both the local project layout and the uploaded repository layout.

## Data note

Review the licensing and privacy requirements for the included CSV files before redistribution.