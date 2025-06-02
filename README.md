netflix_data_EDA
Task 1: Data Cleaning and Preprocessing – Netflix Dataset

📌 Internship Details
Program: Data Analyst Internship  
Duration: 1 Month  
Task: 1 - Data Cleaning and Preprocessing  

 🧾 Objective
To clean and preprocess the Netflix Movies and TV Shows dataset using Python (Pandas). Focus was on missing values, duplicates, formatting, and data types.

 📁 Dataset
- Source: Netflix Movies and TV Shows (Kaggle)
- Raw File: `netflix_titles.csv`
- Cleaned File: `netflix_cleaned.csv`

 🛠 Tools Used
- Google Colab (Python + Pandas)
- Microsoft Excel (optional checks)

 🔧 Cleaning Steps
- Renamed column headers (lowercase, no spaces)
- Removed duplicates
- Filled missing values (`country`, `rating`, `cast`, `director`)
- Converted `date_added` to datetime
- Trimmed whitespaces
- Standardized values in categorical columns like `rating`

 📊 Output
A cleaned and structured dataset ready for analysis.

📂 Files in This Repo
- `task1_cleaning.ipynb`: Python notebook used for cleaning
- `netflix_titles.csv`: Original dataset
- `netflix_cleaned.csv`: Final cleaned dataset
- `screenshots/`: (Optional) Screenshots of Excel usage

📷 Sample Output

| Column        | Issue         | Fix                     |
|---------------|---------------|--------------------------|
| `country`     | Missing values| Filled with "Unknown"    |
| `rating`      | Missing/UR    | Replaced with "Not Rated"|
| `date_added`  | Inconsistent  | Converted to datetime    |
| Duplicates    | Present       | Removed                  |

 ✅ Outcome
Cleaned dataset is ready for EDA, dashboarding or modeling.

