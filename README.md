# 🚌 Public Transit Delay — Exploratory Data Analysis (EDA)

This repository contains a **structured exploratory data analysis** of public transit delay data. The project focuses on cleaning raw delay data, engineering useful features, and producing clear visualizations and insights to understand when, where, and how delays occur. The workflow is organized into **two Jupyter notebooks** and a clean folder structure suitable for portfolio use.

---

## 🎯 Project Overview

The goal of this project is to:

- **Load and clean** raw public transit delay data and document data quality issues (missing values, types, outliers).
- **Engineer features** (e.g. time-based, delay categories) to support analysis and future modeling.
- **Explore** the cleaned dataset through well-labeled visualizations and short written insights.
- **Summarize key findings** in a clear, reproducible way that can inform operational or modeling next steps.

The repository is designed to be **clean, professional, and portfolio-ready**, with placeholders where analysis and plots will be filled in once the dataset is defined and run.

---

## 📥 Dataset Source

*(Add the source of your dataset here — e.g. open data portal URL, Kaggle link, or internal data description. Include any citation or license requirements.)*

- **Source:** *(placeholder)*
- **License / attribution:** *(placeholder)*

---

## ✨ Objectives

| Objective | Description |
|-----------|-------------|
| Data cleaning | Assess missing values, fix types, handle duplicates and invalid entries |
| Feature engineering | Create time-based and delay-related features for EDA and modeling |
| Exploratory analysis | Produce 4–6 well-labeled plots with short insights |
| Key findings | Document main patterns (temporal, by route, on-time performance) |

---

## 🧱 Project Structure

```
public-transit-delay-eda/
│
├── data/
│   ├── raw/                    # Unmodified input data (place raw files here)
│   └── processed/              # Cleaned dataset (e.g. transit_delays_cleaned.csv)
│
├── figures/                    # Exported plots (optional)
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb   # Load, clean, feature engineering, save to processed/
│   └── 02_eda.ipynb            # EDA with 4–6 plots and Key Findings summary
│
├── reports/                    # Project documentation and reports
│
├── src/                        # Reusable utilities (optional, for later use)
│
├── .gitignore
├── README.md
└── requirements.txt
```

> 🗒️ **Note:**  
> Run **`01_data_cleaning.ipynb`** first to generate the cleaned dataset in `data/processed/`. Then run **`02_eda.ipynb`** for exploratory analysis and key findings.

---

## 📊 Key Findings

*(Placeholder — fill in after running the EDA notebook.)*

| Finding | Summary |
|---------|---------|
| Delay distribution | *(e.g. Right-skewed; most trips on time or slightly delayed.)* |
| Temporal patterns | *(e.g. Peak hours and weekdays show higher delays.)* |
| Route/location | *(e.g. Certain routes concentrate high delays.)* |
| On-time performance | *(e.g. X% of trips on time.)* |

---

## 🚀 Next Steps

- **Define data source:** Add the actual raw dataset to `data/raw/` and document its source in this README.
- **Run cleaning notebook:** Execute `01_data_cleaning.ipynb` and adjust cleaning/feature steps to match your schema.
- **Run EDA notebook:** Execute `02_eda.ipynb`, replace plot placeholders with real visualizations, and fill in insights and Key Findings.
- **Optional:** Add `src/` modules for shared loading/plotting utilities; export figures to `figures/` and reference them in `reports/`.
- **Optional:** Extend with modeling (e.g. predicting delay or classifying on-time vs delayed) in a follow-up project.

---

## 🧠 Tech Stack

- **Language:** Python 3.11
- **Libraries:**  
  - `pandas`, `numpy` — data manipulation  
  - `matplotlib`, `seaborn` — visualizations  
  - Jupyter — notebooks
- **Environment:** Jupyter Notebook / VS Code / Cursor
- **Version control:** Git + GitHub

---

## 🧾 License

*(Add your license here, e.g. MIT, or “Data subject to provider terms.”)*

---

## 👤 Author

**Ilian Khankhalaev**  
*BSc Computing Science, Simon Fraser University*  
📍 Vancouver, BC  |  [florykhan@gmail.com](mailto:florykhan@gmail.com)  |  [GitHub](https://github.com/florykhan)  |  [LinkedIn](https://www.linkedin.com/in/ilian-khankhalaev/)
