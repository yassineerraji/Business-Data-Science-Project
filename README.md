## Glassdoor Data Science Salaries — Final Project

A concise, reproducible analysis of data science job salaries based on a cleaned Glassdoor dataset, delivered as a single Jupyter notebook.

### What’s inside
- `notebook.ipynb`: the full exploration and analysis
- `Glassdoor_Salary.csv`: cleaned dataset used by the notebook
- `report.tex`: optional LaTeX report scaffold
- `venv/`: optional local virtual environment (you can use it or create your own)

### Quick start
1) Activate an existing env (recommended):

```bash
source venv/bin/activate
```

2) Or create your own env and install basics:

```bash
python3 -m venv venv
source venv/bin/activate
pip install --upgrade pip
pip install jupyter pandas numpy matplotlib seaborn scikit-learn
```

3) Open the notebook:

```bash
jupyter notebook notebook.ipynb
```

### Data
- File: `Glassdoor_Salary_Cleaned_Version.csv`
- Example columns: `Job Title`, `Salary Estimate`, `Job Description`, `Rating`, `Company Name`, `Location`, `Size`, `Founded`, `Industry`, `Sector`, `Revenue`, `min_salary`, `max_salary`, `avg_salary`, `job_state`, `python_yn`, `R_yn`, `spark`, `aws`, `excel`
- Load in Python:

```python
import pandas as pd
df = pd.read_csv("Glassdoor_Salary_Cleaned_Version.csv")
```

### Reproducibility notes
- Tested on macOS with Python 3.x.
- If a cell references additional libraries, install them with `pip install <package>`.
- Keep the CSV in the same directory as the notebook (or update the path accordingly).