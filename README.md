# Walmart Sales Forecasting

An exploratory sales forecasting project built with Python and Jupyter. The notebook loads Walmart store, feature, training, and test data for analysis and model development.

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

Install the Python dependencies with:

```bash
python -m pip install pandas numpy jupyter
```

## Run the notebook

1. Clone or download this repository.
2. Open `Notebook.ipynb` in Jupyter or VS Code.
3. Select the project Python environment as the notebook kernel.
4. Run the cells from top to bottom.

The notebook uses relative paths such as `Data/train.csv`, so run it with the repository root as the working directory.

## Data note

The included CSV files are provided for this project and should be reviewed for licensing and privacy requirements before redistribution.
