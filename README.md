# Machine Learning and NLP Projects

A collection of practical projects exploring machine learning, natural language processing, and transformer-based models using Python.

## Projects

### 1. Analyzing Car Reviews with LLMs
**Folder:** `car-reviews-sentiment-llm/`

Uses pretrained Hugging Face models to:
- Classify customer car reviews as positive or negative.
- Evaluate sentiment predictions using accuracy and F1 score.
- Translate English text into Spanish.
- Answer questions using a review as context.

**Main notebook:** `Analyzing_car_reviews_with_LLMs.ipynb`

### 2. Heart Disease Prediction
**Folder:** `heart-disease-prediction/`

Explores a supervised machine learning workflow:
- Data preprocessing and one-hot encoding.
- Decision Tree, Random Forest, and XGBoost models.
- Model evaluation and hyperparameter tuning.

**Main notebook:** `HeartDisease_Project.ipynb`

The dataset is not included. Follow the instructions in that project's README to obtain `heart.csv`.

## Getting started

Each project has its own README with its dependencies and run instructions. A typical setup is:

```bash
python -m venv .venv
```

Activate the environment, then install the dependencies listed in the relevant project README.

Open the notebook with Jupyter:

```bash
jupyter notebook
```

## Repository structure

```text
.
├── README.md
├── .gitignore
├── car-reviews-sentiment-llm/
│   ├── README.md
│   └── Analyzing_car_reviews_with_LLMs.ipynb
└── heart-disease-prediction/
    ├── README.md
    └── HeartDisease_Project.ipynb
```

## Notes

- Pretrained Hugging Face models may download model files the first time the notebook runs.
- The heart disease dataset is intentionally not bundled; see its project README.
- The heart disease notebook is an educational machine learning exercise, not a clinical diagnostic tool.
