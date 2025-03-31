# A-B-Testing
Apply an A/B Test and a post-hoc test to four websites versions to determine which one has the best CTR and less Homepage-return Rate
# Eniac Case Study: Chi-Square Hypothesis Testing

## 📌 Project Overview
This project applies a **Chi-Square Test** to analyze data from the Eniac case study. The goal is to determine whether there is a statistically significant difference in click-through rates (CTR) across different versions of a website. Post-hoc corrections are applied to perform pairwise comparisons and identify the true winner.

## 📊 Methodology
1. **Define Hypotheses**
   - **Null Hypothesis ($H_0$):** The click-through rates for all website versions are equal.
   - **Alternative Hypothesis ($H_A$):** At least one version has a different click-through rate.

2. **Select Significance Level**
   - Chosen alpha ($\alpha$) value for statistical testing.

3. **Perform Chi-Square Test**
   - Use contingency tables to analyze categorical data.
   - Calculate expected vs. observed frequencies.

4. **Apply Post-Hoc Analysis**
   - Conduct pairwise comparisons if the null hypothesis is rejected.
   - Use Bonferroni correction (or similar) to control for Type I errors.

5. **Interpret Results**
   - Assess statistical significance and real-world implications.

## 🔧 Dependencies & Installation
To run this notebook, ensure you have the following Python libraries installed:

```bash
pip install pandas numpy scipy seaborn matplotlib
```

## 🚀 Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/Hassan-Merai/A-B-Testing
   ```
2. Navigate to the project folder:
   ```bash
   cd A-B-Testing
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook 7_eniac_case.ipynb
   ```
4. Run all cells to execute the analysis.

## 📈 Results
- Summary of statistical findings.
- Visualizations of observed vs. expected distributions.
- Insights from post-hoc analysis.

## 📝 Authors
- **Hassan Merai// Fred** – [GitHub Profile](https://github.com/Hassan-Merai)
