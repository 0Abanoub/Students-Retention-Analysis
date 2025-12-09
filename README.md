# 🎓 Students Retention Analysis: Mitigating Attrition and Revenue Loss

## Project Overview

This project aims to **identify and quantify the primary factors driving first-year student attrition** (non-retention) and translate these risks into concrete **business costs** (potential revenue loss). The analysis provides data-driven insights and actionable recommendations for academic advisors and university administration to intervene effectively, specifically targeting financial, academic, and demographic high-risk cohorts.

---

## 🚀 Key Findings (The Bottom Line)

The comprehensive analysis identified a **\$8.67 Million total potential revenue loss** due to student attrition. Key risk drivers include:

* **Financial Stress:** The **Extreme Unmet Need** cohort has a retention rate of **72.8%**. Over **77%** of all students report **High Financial Stress**.
* **Academic Barriers:** **Killer Courses** like ASTR 1305 and CPSC 1301L exhibited failure rates near **100%**, acting as critical academic bottlenecks.
* **Momentum Loss:** Students earning **less than 12 credit hours** in their first term have significantly lower retention (**75.7%**).
* **Highest Attrition Group:** Students in **Background Category 5 (BGD 5)** have the lowest retention rate at **50.0%**.

---

## 🛠️ Recommendations for Intervention

The project advocates for a tiered intervention model focusing resources on the **High and Critical Risk** categories (which account for 25% of the total revenue loss risk).

1.  **Financial Aid:** Establish an **Emergency Micro-Grant Fund** targeted specifically at students flagged with Extreme Unmet Need.
2.  **Academic Support:** Implement mandatory, high-intensity **Tutoring/Restructuring** for high D/F rate courses (e.g., ASTR 1305).
3.  **Advising:** Mandate a **First-Term Advising Checkpoint** to ensure all students are on track to earn at least 12 credits.
4.  **Targeted Support:** Assign **Dedicated Success Coaches** to the highest-risk demographic groups (BGD 5/7).

---

## 📁 Repository Structure

| File/Directory | Description |
| :--- | :--- |
| `Preprocessing.ipynb` | Contains data cleaning, feature engineering, handling missing values, and normalization steps. |
| `Analytics.ipynb` | The core analytical notebook featuring all visualizations (Demographic, Academic, Financial, Risk Impact) and the final conclusion/recommendations. |
| `student_retention_DASHBOARD.csv` | The **primary, clean dataset** used for all in-depth analysis and modeling. |
| `data_dictionary_dashboard.csv` | Metadata describing the columns and variables found in the primary dataset. |
| `Student.xlsx` | The raw, original data file (unprocessed). |
| `student_retention_processed_FULL.csv` | Intermediate file used after initial cleaning steps. |
| `summary_*.csv` files | Pre-aggregated summary tables used to generate key visualizations (e.g., `summary_by_risk.csv`, `summary_gateway_courses.csv`). |

---

## 💻 Setup and Usage

This project uses Python and common data science libraries.

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/0Abanoub/Students-Retention-Analysis.git](https://github.com/0Abanoub/Students-Retention-Analysis.git)
    cd Students-Retention-Analysis
    ```
2.  **Install Dependencies:** (Assumes use of Anaconda/Jupyter environment)
    ```bash
    # Example dependencies
    pip install pandas numpy matplotlib seaborn jupyter
    ```
3.  **Run Analysis:**
    * Start with `Preprocessing.ipynb` to understand the data preparation steps.
    * Proceed to `Analytics.ipynb` to view the comprehensive analysis, visualizations, and final findings.

---

## ✍️ Author

* **Author Name:** [Muhammad Seyam/Abanoub]
* **Course:** [Data Analysis - Year 3]