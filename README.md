# SomaTrack: Predicting Study-Related Physical Ailments

## Overview
SomaTrack is a Machine Learning project that predicts the likelihood of students experiencing physical ailments (back pain, neck strain, tension headaches) caused by prolonged sedentary behavior during study sessions. This is a **Multiclass Classification** problem.

## Project Structure
```
SomaTrack/
├── data/                    # Raw and processed datasets
│   ├── raw/                 # Original survey responses (CSV)
│   └── processed/           # Cleaned and engineered datasets
├── notebooks/               # Jupyter notebooks
│   └── SomaTrack.ipynb      # Main analysis notebook
├── models/                  # Trained model files
├── README.md
├── requirements.txt
└── .gitignore
```

## Objectives
- **Primary**: Predict risk level of physical discomfort based on environmental and behavioral factors
- **Data Engineering**: Design a survey converting qualitative pain experiences into quantitative scales
- **Technical**: Practice Feature Selection to identify which habits cause the most pain

## Target Labels
- 0: No Pain
- 1: Mild / Occasional Pain
- 2: Moderate / Frequent Pain
- 3: Severe / Chronic Pain

## Tech Stack
- Python 3.x
- pandas, numpy
- matplotlib, seaborn, plotly
- scikit-learn
- joblib (model persistence)
