# MLDL - Machine Learning & Deep Learning Learning Repository

A structured learning repository for Machine Learning and Deep Learning, managed with `uv`.

## Project Structure

```
MLDL/
├── 01-ml-sklearn/           # Machine Learning (scikit-learn)
│   ├── regression/          # Regression models
│   ├── classification/      # Classification models
│   ├── clustering/          # Clustering algorithms
│   └── preprocessing/       # Data preprocessing
│
├── 02-boosting/             # Boosting algorithms
│   ├── xgboost/             # XGBoost
│   ├── lightgbm/            # LightGBM
│   └── catboost/            # CatBoost
│
├── 03-dl-pytorch/           # Deep Learning (PyTorch)
│   ├── 00-fundamentals/     # PyTorch basics
│   ├── 01-classification/   # Neural network classification
│   ├── 02-computer-vision/  # CNN and image processing
│   ├── 03-custom-datasets/  # Custom dataset handling
│   ├── 04-modular/          # Modular PyTorch code
│   └── 05-transfer-learning/# Transfer learning techniques
│
├── 04-projects/             # Hands-on projects
├── data/                    # Shared datasets
├── utils/                   # Shared utility functions
└── notebooks/               # Experimental notebooks
```

## Environment Setup

This project uses [uv](https://docs.astral.sh/uv/) for Python dependency management.

### Prerequisites

Install uv:
```bash
# macOS/Linux
curl -LsSf https://astral.sh/uv/install.sh | sh

# or with Homebrew
brew install uv
```

### Setup

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/MLDL.git
cd MLDL
```

2. Install dependencies:
```bash
uv sync
```

3. Activate the virtual environment:
```bash
source .venv/bin/activate
```

4. Start Jupyter Lab:
```bash
jupyter lab
```

## Dependencies

- **Core**: numpy, pandas, matplotlib, scikit-learn
- **Deep Learning**: torch, torchvision
- **Boosting**: xgboost, lightgbm, catboost
- **Development**: jupyter

## Learning Progress

### Machine Learning (scikit-learn)
- [x] Linear Regression
- [ ] Logistic Regression
- [ ] Decision Trees
- [ ] Random Forest
- [ ] SVM
- [ ] K-Means Clustering

### Boosting
- [ ] XGBoost
- [ ] LightGBM
- [ ] CatBoost

### Deep Learning (PyTorch)
- [x] PyTorch Fundamentals
- [x] Classification
- [x] Computer Vision (CNN)
- [x] Custom Datasets
- [x] Modular PyTorch
- [x] Transfer Learning

## Notes

- Large data files and model weights are excluded from version control
- Use `data/` for small shared datasets
- Use `notebooks/` for experimental work
