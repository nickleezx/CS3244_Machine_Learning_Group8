# CS3244 Machine Learning Group 8

CS3244 Machine Learning Group Project — Credit Card Approval Prediction

## Project Structure

```
.
├── data/
│   ├── application_record.csv
│   └── credit_record.csv
├── notebook.ipynb
├── environment.yml
└── README.md
```

## Setup

### Prerequisites

- [Anaconda](https://www.anaconda.com/download) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html) installed

### Create the Conda Environment

```bash
conda env create -f environment.yml
```

### Activate the Environment

```bash
conda activate cs3244
```

### Updating the Environment

If new dependencies are added, update your local environment with:

```bash
conda env update -f environment.yml --prune
```

### Exporting the Environment (after installing new packages)

```bash
conda env export > environment.yml
```

## Usage

1. Activate the conda environment: `conda activate cs3244`
2. Launch Jupyter Notebook: `jupyter notebook`
3. Open `notebook.ipynb` to run the analysis pipeline

## Key Dependencies

- Python 3.11
- pandas
- scikit-learn
- imbalanced-learn
- matplotlib
- seaborn
