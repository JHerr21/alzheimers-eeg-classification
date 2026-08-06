# alzheimers-eeg-classification
** Interpretable EEG Classification of Dementia**

Timeline: 8 weeks
Dataset: OpenNeuro ds004504
Outputs: MNE preprocessing pipeline, feature analysis, classical baselines, compact PyTorch model, ablation study, technical report
Success criteria: Subject-level evaluation, no epoch leakage, confidence intervals, reproducible environment, interpretable physiological findings

---

## Project Structure

alzheimers-eeg-classification/
├── README.md
├── LICENSE
├── .gitignore
├── pyproject.toml
├── uv.lock
├── configs/
│   └── baseline.yaml
├── data/
│   └── README.md
├── notebooks/
│   ├── 01_dataset_exploration.ipynb
│   ├── 02_signal_quality.ipynb
│   └── 03_baseline_model.ipynb
├── scripts/
│   ├── download_data.py
│   ├── train.py
│   └── evaluate.py
├── src/
│   └── alzheimers_eeg/
│       ├── __init__.py
│       ├── data.py
│       ├── preprocessing.py
│       ├── features.py
│       ├── models.py
│       ├── evaluation.py
│       └── visualization.py
├── tests/
│   ├── test_preprocessing.py
│   └── test_features.py
├── reports/
│   ├── methodology.md
│   └── figures/
└── results/
    └── README.md