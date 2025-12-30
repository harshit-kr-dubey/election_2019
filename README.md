# Electoral Outcomes and Voter Turnout Analysis (India)

## Overview
This project analyzes constituency-level election data from India to study patterns in voter turnout and electoral outcomes across regions. The objective is to examine regional variation in voter participation and explore demographic correlates that may be associated with turnout and party performance. The project emphasizes **data cleaning, transparent preprocessing, exploratory statistical analysis, and clear documentation**, reflecting a research-oriented workflow.

---

## Research Questions
- How does voter turnout vary across constituencies and regions?
- Are there systematic patterns in party performance and winning margins across regions?
- What demographic characteristics (e.g., income, education, age proxies) are associated with voter participation?

---

## Data
- **Unit of analysis:** Parliamentary constituency  
- **Data sources:** Publicly available election and demographic datasets  
- **Variables include:**
  - Voter turnout (%)
  - Total votes polled
  - Winning margins
  - Party-wise vote shares
  - Demographic proxies (income, education, age distribution)

> Note: All datasets used are secondary and publicly available. Sensitive or personally identifiable information is not included.

---

## Methodology
1. **Data Collection**
   - Compiled constituency-level election data from publicly available sources.
   - Integrated demographic information using consistent geographic identifiers.

2. **Data Cleaning & Preprocessing**
   - Standardized constituency and state names.
   - Handled missing values and inconsistencies.
   - Constructed derived variables for analysis.

3. **Exploratory Data Analysis**
   - Descriptive statistics and distributional analysis of voter turnout.
   - Regional comparisons of turnout and party performance.
   - Identification of swing constituencies using winning margins.

4. **Statistical Analysis**
   - Correlation and exploratory regression analysis to examine relationships between voter turnout and demographic variables.
   - Emphasis on interpretation and limitations rather than causal claims.

5. **Visualization & Reporting**
   - Created research-ready tables and visualizations using Power BI and Python.
   - Focused on clarity and interpretability of results.

---

## Tools & Technologies
- **Programming:** Python (Pandas, NumPy)
- **Databases / Querying:** SQL
- **Visualization:** Power BI, Matplotlib
- **Documentation:** Markdown

---

## Key Findings (Exploratory)
- Substantial regional variation in voter turnout across constituencies.
- Identification of constituencies with narrow winning margins, suggesting potential swing regions.
- Demographic variables show meaningful correlations with voter participation, though results are exploratory and not causal.

---

## Limitations
- Analysis is exploratory and does not establish causal relationships.
- Demographic variables are proxies and may not fully capture underlying voter characteristics.
- Data quality varies across regions and election cycles.

---

## Future Work
- Extension to panel data across multiple election years.
- Application of quasi-experimental methods (e.g., Difference-in-Differences) for policy evaluation.
- Incorporation of textual analysis of candidate or party manifests.

---

## Author
**Harshit Kr Dubey**  
B.Tech, Computer Science Engineering  
GitHub: https://github.com/harshit-kr-dubey

---

## License
This project is intended for academic and research purposes only.
