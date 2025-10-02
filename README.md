# Business Insights Analytics

This repository provides a complete, ready-to-use project for business analytics and program management professionals. It includes a synthetic dataset, exploratory data analysis (EDA), visualizations, and predictive modeling. The project is designed with increasing complexity to showcase skills relevant for roles such as **Business Analyst**, **Program Manager**, and **Data Analyst**.

## Getting started

1. **Clone the repository** (or download it as a ZIP file).
2. Install the required Python packages:

```bash
pip install -r requirements.txt
```

3. Navigate to the `notebooks` directory and open the analysis notebook:

```bash
cd notebooks
jupyter notebook analysis.ipynb
```

## Project structure

```
business-insights-analytics/
├── data/
│   └── synthetic_projects.csv   # Synthetic dataset
├── notebooks/
│   └── analysis.ipynb           # Jupyter notebook with EDA and models
├── requirements.txt             # Python dependencies
└── README.md                    # Project overview and instructions
```

## Dataset overview

The dataset (`synthetic_projects.csv`) simulates 1,000 projects across various industries. Each row represents a project with attributes such as budget, duration, team size, complexity, risk score, stakeholder engagement level, and whether the project was successful. The dataset is intentionally simplified yet realistic enough to practice data analysis techniques.

Key columns:

- **project_id**: Unique ID for each project
- **industry**: Sector (Finance, Healthcare, Technology, Retail, Manufacturing)
- **team_size**: Number of team members
- **budget_k**: Project budget (thousands of dollars)
- **duration_months**: Project duration in months
- **complexity**: Project complexity score (1–10)
- **vendor_count**: Number of external vendors
- **risk_score**: Risk score (0–1)
- **stakeholder_engagement**: Stakeholder engagement level (1–5)
- **actual_cost_k**: Actual cost incurred (thousands of dollars)
- **success**: Binary indicator of project success
- **satisfaction**: Stakeholder satisfaction score (0–10)

## Analysis notebook

The Jupyter notebook walks through:

1. Loading and inspecting the dataset.
2. Performing basic EDA with summary statistics.
3. Visualizing distributions, relationships, and correlations.
4. Preparing data for modeling (one-hot encoding, train/test split).
5. Building and evaluating two models:
   - Logistic Regression (baseline classifier)
   - Random Forest Classifier (more advanced)
6. Interpreting results and discussing potential next steps.

The notebook is intentionally commented and structured to guide readers through each step. Feel free to modify the notebook, experiment with different models, or extend the analysis for more advanced applications.

## Use cases and difficulty levels

- **Beginner**: Focus on understanding the dataset, calculating summary statistics, and creating basic visualizations.
- **Intermediate**: Build the logistic regression model and interpret coefficients.
- **Advanced**: Explore the random forest model, tune hyperparameters, or add additional algorithms (e.g., gradient boosting, SVM). You can also engineer new features or perform cross-validation.

## License

This project is provided for educational purposes. Feel free to use and modify it for learning and portfolio-building.
