# AI in Software Engineering – Week 4 Assignment  
**Theme:** *Building Intelligent Software Solutions* :computer: :robot:

This repository contains my deliverables for Week 4 of the AI in Software Engineering course.  
The goal is to demonstrate how AI techniques can automate tasks, enhance decision‑making, and address practical challenges in software development.

---

## 📁 Repository Layout

| Path | Purpose |
|------|---------|
| `task1_completion/` | Manual and AI‑generated Python snippets for sorting a list of dictionaries. |
| `task2_testing/` | Selenium IDE + Testim AI test script (`login_test.side`) and summary. |
| `task3_analytics/` | Jupyter notebook / script for predictive analytics on the Breast‑Cancer dataset. |
| `reports/` | PDF report, screenshots, and metrics JSON. |
| `data/` | **`breast_cancer.csv`** (local copy of the dataset). |
| `README.md` | Project overview (this file). |
| `LICENSE` | MIT License. |

---

## 🚀 Quick Start

```bash
# 1 – Clone the repo
git clone https://github.com/<your‑username>/ai‑se‑week4.git
cd ai‑se‑week4

# 2 – Create or activate a Python 3.11+ venv
python -m venv .venv && source .venv/bin/activate

# 3 – Install requirements
pip install -r requirements.txt   # or run the one‑liner below
```

> **One‑liner install (no requirements.txt):**
> ```bash
> pip install "numpy>=2.0.0" "pandas>=2.3.0" "scikit-learn>=1.4.0" matplotlib seaborn
> ```

---

## 📊 Running the Tasks

### Task 1 – AI‑Powered Code Completion
```bash
python task1_completion/manual_sort.py
python task1_completion/copilot_sort.py
```
Compare runtime and readability; analysis in `reports/task1_analysis.md`.

### Task 2 – Automated UI Testing
Open `task2_testing/login_test.side` in Selenium IDE or upload to Testim.io.  
Execution screenshots live in `reports/`.

### Task 3 – Predictive Analytics
```bash
# Option A – Notebook
jupyter notebook task3_analytics/bc_priority.ipynb
# Option B – Script
python task3_analytics/bc_priority.py
```
Outputs accuracy/F1 scores and a feature‑importance plot.

---

## 🧑‍⚖️ Ethical Reflection
See **Section 3** of `reports/Week4_AI_in_Software_Engineering_Assignment.pdf` for bias analysis and mitigation using IBM AIF360.

---

## 📝 Dependencies

| Package | Tested Version |
|---------|----------------|
| Python  | 3.11 |
| NumPy   | ≥ 2.0.0 |
| pandas  | ≥ 2.3.0 |
| scikit‑learn | ≥ 1.4.0 |
| matplotlib | ≥ 3.7 |
| seaborn | ≥ 0.12 |

---

## 🔄 Re‑creating the Environment (online Jupyter)

If the system env is read‑only:

```python
%pip install --user --no-cache-dir -I "numpy>=2.0.0" "pandas>=2.3.0" "scikit-learn>=1.4.0"
# then restart the kernel
```

---

## 📜 License
This project is licensed under the **MIT License** – see `LICENSE` for details.

---

## 🙋‍♂️ Author
Ray – Computer Science graduate, PLP Academy Cohort Feb 2025.  
For questions reach out on the course community Slack (#AISoftwareAssignment).  
