
## Project setup
The project uses python 3.8.5 You need to have it installed on your machine.
In order to run you need for fetch the dataset (requires setting up an account at Data World)
and creating a virtual environment.

### Fetching the dataset
The dataset orignates from [Kaggle](https://www.kaggle.com/santoshd3/bank-customers?select=Churn+Modeling.csv).

### Run the notebooks
```
python3.8 -m venv env
source env/bin/activate
pip install -r requirements.txt

jupyter notebook
```

## Content
There are two notebooks there.
The `01-initial-exploration.ipynb` explores and cleans the dataset.
It also creates a new, processed dataset under `data/X_raw.pkl` and `data/Y_raw.pkl.
Then, the `02-evaluating_models.ipynb` is the actual answers to the questions.
It requries the previously the generated files.

