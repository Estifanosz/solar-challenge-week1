#  Solar Challenge Week 1 – Git & Environment Setup

##  Folder Structure

```bash
solar-challenge-week1/
├── .github/
│   └── workflows/
│       └── ci.yml                # GitHub Actions workflow for CI
├── .gitignore                    # Git ignored files and folders
├── requirements.txt              # Project dependencies
├── README.md                     # Project overview and setup
├── notebooks/
│   ├── __init__.py
│   └── README.md                 # Notebook usage guide
├── src/                          # Source code directory
├── tests/
│   └── __init__.py               # Test suite (to be expanded)
└── scripts/
    ├── __init__.py
    └── README.md                 # Script usage guide

```

## Environment Setup Instructions

### Follow these steps to set up the project locally:

1. Clone the repository

```bash
git clone https://github.com/Estifanosz/solar-challenge-week1.git
cd solar-challenge-week1
```

2. Create a virtual environment (venv)

```bash
python -m venv venv
```

3. Activate the environment

   venv\Scripts\activate.bat


4. Install dependencies

```bash
pip install -r requirements.txt
```

Continuous Integration (CI)

This project uses GitHub Actions to run a basic CI pipeline.

The workflow file is located at:

```bash
.github/workflows/ci.yml
```

The pipeline:

- Checks out the code

- Sets up Python

- Installs requirements

- Verifies Python installation
  Project Context

This repository will be extended with:

- Exploratory Data Analysis (EDA) notebooks

- Data processing scripts




Author

    Estifanos Zerihun
