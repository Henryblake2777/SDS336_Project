# SDS336 Project

Loan delinquency analysis (Lending Club `loans_full_schema.csv`, 10,000 rows × 55 cols).
Target: `delinquency` = late payment status OR paid late fees (149 positives, ~1.5%).

## Layout

| Path | What it is | Hub role |
|------|------------|----------|
| `SDS336_Project_Midterm.ipynb` | Cleaning, feature engineering, EDA, (commented-out) RF / XGBoost models | `data` |
| `.claude/hub/` | Multi-agent hub manifest and grants | coordinator |

Data file is not in the repo; the notebook reads it from an absolute path outside the project.
