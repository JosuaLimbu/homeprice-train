# Train Dataset Banglore Home Price Prediction

This repository contains code for training a home price prediction model using the Bengaluru House Price dataset. The dataset can be found [here](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data).

## Getting Started

This repository uses Python 3.11

- We use [pyenv](https://github.com/pyenv/pyenv) and [pyenv-virtualenv](https://github.com/pyenv/pyenv-virtualenv) to manage Python versions and virtual environments.
- The `requirements.txt` is provided to install dependencies easily.

## Usage

1. First, install all dependencies from `requirements.txt`:

```bash
pip install -r requirements.txt
```

2. Download the dataset from [here](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data) and place it in the same directory as the training code.
3. Run the Jupyter Notebook to train the model:

```bash
jupyter notebook training_home_prices_final.ipynb
```

4. Follow the instructions in the notebook to preprocess data, train the model, and evaluate its performance.

## Web Deployment

The trained model is implemented in a web application, available [here](https://github.com/JosuaLimbu/homeprice-predict).
