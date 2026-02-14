# Synthetic Data Generation

A project for generating synthetic data from common statistical distributions.

## Setup

This project uses `uv` for fast Python package management.

### Prerequisites

- Python 3.12+
- uv (install from https://github.com/astral-sh/uv)

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd Synthetic-Data-Generation
```

2. Create and activate the virtual environment:
```bash
uv venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

3. Install dependencies:
```bash
uv pip install -r requirements.txt
```

4. Create Jupyter kernel:
```bash
python -m ipykernel install --user --name=synthetic-data-gen --display-name="Synthetic Data Generation"
```

## Usage

Open the Jupyter notebook:
```bash
jupyter notebook statistical_distributions.ipynb
```

Make sure to select the "Synthetic Data Generation" kernel when running the notebook.

## Distributions Covered

- **Normal Distribution**: Heights of adults
- **Log-Normal Distribution**: Income distribution
- **Binomial Distribution**: Product quality control
- **Poisson Distribution**: Customer arrivals per hour

## Project Structure

```
Synthetic-Data-Generation/
├── statistical_distributions.ipynb  # Main notebook with all distributions
├── requirements.txt                 # Python dependencies
├── .gitignore                       # Git ignore rules
└── README.md                        # This file
```

#
