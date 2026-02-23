# MSIN0097-Assessment1-Individual-Coursework- Credit Default Prediction

## Project Overview

This project develops and evaluates predictive models to estimate the probability of credit card default using the Taiwan Credit Card Default dataset.

The analysis follows a structured six-stage workflow:

1. Obtain dataset and define predictive problem  
2. Explore and visualise the data  
3. Prepare the data  
4. Train and compare candidate models  
5. Fine-tune the best-performing model  
6. Present final evaluation and conclusions  

An agentic methodology was applied at structured decision points.  
Agent suggestions were consulted during metric selection, leakage validation, pipeline construction, hyperparameter tuning, and debugging.  
All final modelling decisions remained human-supervised.

---

## Repository Structure

```
credit-default-project/
│
├── notebooks/
│   └── credit_default_analysis.ipynb
│
├── requirements.txt
└── README.md
```

Note:  
The dataset is not stored in this repository.

---

## Data Access

This project uses the **Default of Credit Card Clients Dataset**.

Source (Kaggle):  
https://www.kaggle.com/datasets/uciml/default-of-credit-card-clients-dataset

License: **CC0 1.0 Universal (Public Domain)**  
https://creativecommons.org/publicdomain/zero/1.0/

The dataset is licensed under CC0 (Public Domain).  
It is not redistributed in this repository to maintain repository cleanliness and best practices.

### To reproduce the analysis:

1. Download the dataset from Kaggle.
2. Extract the CSV file.
3. Rename the file to:

```
credit_default.csv
```

4. In the project root directory, create a folder named:

```
data
```

5. Place the file inside that folder:

```
project-root/
└── data/credit_default.csv
```

The notebook assumes this exact structure.

---

## Environment Setup

Python 3.9+ recommended.

Install required libraries:

```bash
pip install -r requirements.txt
```

---

## How to Run

1. Clone the repository.

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Download and place the dataset as described in the **Data Access** section.

4. Open the notebook located in:

```
notebooks/credit_default_analysis.ipynb
```

5. Run all cells sequentially from top to bottom.

The notebook assumes it is executed from within the `notebooks/` directory and that the dataset is located at:

```
../data/credit_default.csv
```

All preprocessing, model training, evaluation, and visualisations are generated dynamically within the notebook.
