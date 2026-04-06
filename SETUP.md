# Setup Instructions

## Prerequisites
- Python 3.10+
- Git
- pip

## Clone the repository
```bash
git clone https://github.com/Alierkn/Data-Mining-Lesson-Unime.git
cd Data-Mining-Lesson-Unime
```

## Create a virtual environment
### macOS / Linux
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### Windows
```bash
python -m venv .venv
.venv\\Scripts\\activate
```

## Install dependencies
```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

## Run Jupyter
```bash
jupyter notebook
```

Then open the notebooks in this order:
1. `notebooks/NB1_L1_DataExploration.ipynb`
2. `notebooks/NB2_L2_DataCleaning.ipynb`
3. `notebooks/NB3_L3_Regression_GradientDescent.ipynb`
4. `notebooks/NB4_Capstone_FullPipeline.ipynb`

## Notes
- The notebooks load datasets directly from public sources or from `scikit-learn`.
- For reproducibility, install the dependencies inside the project virtual environment.
