# Titanic Data Workflow

This project uses Python to explore the Titanic passenger dataset. It includes reusable cleaning functions, exploratory summaries, and three labeled visualizations. The analysis examines recorded ages and survival percentages by sex and passenger class.

Dataset: [Titanic passenger data from the Seaborn example repository](https://github.com/mwaskom/seaborn-data/blob/master/titanic.csv).

## How to run

Use Python 3.11 and keep `titanic.csv` in the same folder as `data_workflow.ipynb`.

Create and activate an environment in Windows Command Prompt:

```bat
python -m venv .venv
.venv\Scripts\activate.bat
```

Install the dependencies:

```bat
pip install -r requirements.txt
```

Start Jupyter Notebook:

```bat
python -m notebook
```

Open `data_workflow.ipynb`, restart the kernel, and run all cells from top to bottom. The notebook displays the results and saves three PNG figures in the project folder.

## Record dependencies

After changing packages in the project environment, regenerate the dependency file:

```bat
pip freeze > requirements.txt
```
