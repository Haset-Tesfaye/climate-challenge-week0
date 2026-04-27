# Climate Challenge Week 0

## Project Overview

This project analyzes historical climate data from Ethiopia, Kenya, Sudan, Tanzania, and Nigeria to identify trends, variability, and climate risks in preparation for COP32.

---

## Setup Instructions

### 1. Clone Repository

```bash
git clone https://github.com/your-username/climate-challenge-week0.git
cd climate-challenge-week0
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

Activate:

```bash
venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Project Structure

```
├── notebooks/       # Jupyter notebooks for analysis
├── data/            # Cleaned datasets (ignored in Git)
├── scripts/         # Helper scripts
├── tests/           # Unit tests
├── .github/workflows/  # CI/CD pipeline
```

---

## Running the Analysis

Open Jupyter Notebook:

```bash
jupyter notebook
```

Then navigate to:

```
notebooks/ethiopia_eda.ipynb
```

---

## Tools Used

* Python (pandas, numpy, matplotlib, seaborn)
* Jupyter Notebook
* Git & GitHub
* VS Code

---

## Notes

* Raw and cleaned datasets are excluded using `.gitignore`
* CI pipeline validates environment setup
