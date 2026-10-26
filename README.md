# Valentius Kryptix — Internship Tasks

This repository contains deliverables for internship assignments.

## Task 1: Exploratory Data Analysis (EDA)
A complete exploratory analysis of the Netflix Movies and TV Shows dataset using Python, Pandas, and Matplotlib.

- **Notebook:** [EDA_Netflix.ipynb](./EDA_Netflix.ipynb)
- **Dataset:** [Netflix Movies and TV Shows on Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Dependencies:** See [requirements.txt](./requirements.txt)

### Run
Open the notebook in [Google Colab](https://colab.research.google.com/) or Jupyter. It attempts to download the dataset with `kagglehub`; if automatic download fails, download `netflix_titles.csv` from Kaggle and upload/place it as prompted.

### Analysis includes
- Dataset shape, schema, first/last rows, and memory footprint
- Missing value and duplicate analysis
- Numeric summaries and categorical value counts
- At least six visualizations, each with a question and data-derived interpretation
- Automatically generated key findings and limitations

**Before submitting:** Run the notebook top-to-bottom and review its generated findings against the charts. These describe the catalog dataset, not viewer popularity or watch time.
