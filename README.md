# turkish-super-league-salary-analysis
Data Analysis on Turkish Super League Football Player Salaries (2024–25)
# 🏟️ Turkish Super League Player Salary Analysis (2024–2025)

This project analyzes salary, contract, and bonus data for football players in the **Turkish Super League** during the 2024–2025 season. Using Python and Jupyter Notebook, I cleaned and explored the dataset, created visualizations, and extracted meaningful insights around player earnings and contract structures.

---

## 📁 Dataset Description

The dataset contains verified salary information of players, including:

| Column                    | Description                                               |
|---------------------------|-----------------------------------------------------------|
| Player_Name               | Full name of the player                                   |
| Verified_Salary           | Whether the salary is verified                            |
| Weekly_Earning_EUR        | Weekly gross salary in Euros                              |
| Yearly_Earning_EUR        | Yearly gross salary in Euros                              |
| Bonus_Earning_EUR         | Annual bonus in Euros                                     |
| Signing_Date              | Date the contract was signed                              |
| Expiration_Date           | Contract expiration date                                  |
| Years_Remaining           | Remaining contract duration in years                      |
| Gross_Remaining_EUR       | Total remaining gross fee on the contract                 |
| Release_Clause_EUR        | Value of the player's release clause (if available)       |
| Status / Position / Club  | Player role, field position, and club                     |

---

## 🚀 Project Objectives

- ✅ Clean raw data and convert currency/date columns to usable formats  
- ✅ Perform exploratory data analysis (EDA) on salary and contract trends  
- ✅ Visualize player earnings, bonuses, contract lengths, and club comparisons  
- ✅ Filter and extract actionable insights (e.g., players with short contracts and high salaries)

---

## 🛠️ Tools Used

- **Python**
- **Jupyter Notebook**
- **pandas**
- **matplotlib**
- **seaborn**

---

## 📊 Key Visualizations

- Top 10 highest paid players by yearly salary
- Bonus vs Yearly Salary scatter plot
- Weekly salary distribution histogram
- Contract duration distribution
- Total salary spending by club (bar chart)
- Correlation matrix of numerical variables

---

## 🔍 Example Insights

- Some players earn over **€10M per year**, with **release clauses undisclosed**
- A few clubs dominate the top salary brackets (Galatasaray, Besiktas, etc.)
- Several high-earning players have **1 year or less remaining** on their contracts

---

## 📂 Files in This Repository

- `Turkish_Super_League_Salary_Analysis.ipynb` – Main Jupyter Notebook with full analysis
- `turkish_superleague_salaries.csv` – Raw or cleaned dataset (optional)
- `README.md` – This documentation

---

## 📌 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/25akanksha/turkish-super-league-salary-analysis.git
