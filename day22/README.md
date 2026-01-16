## Day 22 – Exploratory Data Analysis (EDA)

This day focuses on understanding datasets through Exploratory Data Analysis (EDA) and learning the practical limitations of automated EDA tools.

The goal was not just to generate plots, but to critically evaluate EDA tools and understand when manual analysis is more effective.

---

### What was covered

- Dataset inspection and basic statistics
- Automated EDA using **YData / Pandas Profiling**
- Understanding correlations and distributions
- Identifying missing values and data quality issues
- Manual EDA using pandas and visualization libraries

---

### Important Note on Pandas / YData Profiling

While Pandas Profiling (now YData Profiling) can be useful for quick dataset overviews, it has **practical limitations**:

- Limited support for newer pandas/numpy versions
- Instability with text and object-type columns
- Heavy HTML reports with broken or unreliable UI interactions
- Not suitable for production or presentation use

In this project, profiling was used **only for initial sanity checks**, and insights were validated using **manual EDA**, which is the preferred approach in real-world workflows.

---

### Dataset Used

- Iris Dataset (for clean and stable EDA)
- Sample CSV for experimentation

---

### Files in this folder

- `day22.ipynb` – EDA notebook
- `eda_report.html` – Auto-generated profiling report (for reference only)
- `iris_eda_report.html` – Profiling on Iris dataset
- `train.csv` – Dataset used for analysis

---

### Key Takeaways

- Automated EDA tools are optional, not essential
- Manual EDA provides clearer insights and better control
- Understanding tool limitations is an important data skill

---

### Learning Outcome

Developed a practical mindset towards EDA by balancing automation with manual analysis and focusing on interpretability rather than tool dependency.
