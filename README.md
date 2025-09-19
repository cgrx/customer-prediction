# Customer Prediction

## About
Materials used during workshop on customer prediction.

## Setup
- Install `uv` for project management. 
```shell
curl -LsSf https://astral.sh/uv/install.sh | sh
```
- Install `python 3.12` and its dependencies.
```shell
uv python install 3.12
```
- Create and activate a virtual environment.
```shell
uv venv
source .venv/bin/activate
```
- Install the project dependencies.
```shell
uv sync
```

## Usage
- Run jupyter notebook.
```shell
uv run jupyter notebook
```
- This command will start a jupyter server and open the interface in your default web browser.
- Index of notebooks:
  - `eda.ipynb`: Exploratory Data Analysis on the customer dataset.
  - `feature.ipynb`: Data wrangling and feature engineering.
  - `model.ipynb`: Model training and evaluation.
- You can run the cells in the notebooks sequentially to see the analysis and results.

## Note
- Ensure you have a stable internet connection to download any required packages.
- After closing the browser, you can stop the jupyter server by pressing `Ctrl + C` in the terminal where it is running.
