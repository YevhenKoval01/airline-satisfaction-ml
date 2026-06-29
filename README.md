# Airline Passenger Satisfaction ML

An end-to-end machine learning notebook for analyzing airline passenger satisfaction. The project covers exploratory data analysis, data cleaning, feature engineering, model comparison, hyperparameter tuning, final evaluation, and model explainability.

## Tech Stack

- Python
- Jupyter Notebook
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn

## Project Structure

```text
data/
  raw/
    .gitkeep
reports/
  final_report.pdf
airline_passenger_satisfaction.ipynb
requirements.txt
README.md
```

## Dataset

The notebook expects two local files:

```text
data/raw/train.csv
data/raw/test.csv
```

Place them in the `data/raw/` folder before running the notebook. These files are ignored by Git, so the repository stays clean if the dataset license does not allow redistribution.

## How To Run

1. Install Python 3.10 or newer.
2. Create and activate a virtual environment:

   ```bash
   python -m venv .venv
   .\.venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Add `train.csv` and `test.csv` to the `data/raw/` folder.
5. Start Jupyter:

   ```bash
   jupyter notebook
   ```

6. Open `airline_passenger_satisfaction.ipynb`.
7. Run the notebook cells from top to bottom.

