# 🚗 Vehicle Insurance Exploratory Analysis

This repository presents a comprehensive **Exploratory Data Analysis (EDA)** of a vehicle insurance dataset. The primary objective is to uncover trends in customer demographics, understand behavior patterns, and derive meaningful insights that can assist insurance companies in making informed business decisions.

---

## 🧾 Project Overview

In the era of data-driven decision-making, insurance companies collect vast amounts of customer information to enhance their services and maximize profitability. This project focuses on analyzing a real-world dataset containing demographic details, vehicle conditions, and insurance status of individuals.

By applying data cleaning, statistical analysis, and visual storytelling, the project answers the following key questions:
- What factors influence the likelihood of someone purchasing vehicle insurance?
- How do customer attributes like age, gender, region, and vehicle damage history affect insurance ownership?
- Can we segment potential customers for more effective targeting?

The analysis not only provides insights but also proposes business strategies based on patterns observed in the dataset.

---

## 📁 Project Structure

```
📦 Vehicle-Insurance-EDA
├── Vehicle_Insurance (3).csv     # Raw dataset in CSV format
├── PFA(Mini_Project).ipynb       # Jupyter Notebook with full code and analysis
├── README.md                     # Project documentation
```

---

## 🧰 Tools & Libraries Used

The project was implemented using Python, leveraging powerful data science libraries:

| Library       | Purpose |
|---------------|---------|
| `pandas`      | Data loading, cleaning, transformation, and exploration |
| `numpy`       | Numerical computation and basic statistical operations |
| `matplotlib`  | Basic visualizations like bar charts and pie charts |
| `seaborn`     | Advanced statistical visualizations (e.g., histograms, heatmaps) |
| `warnings`    | Suppressing unnecessary system warnings during analysis |

---

## 📊 Analysis Breakdown

### 1. 📂 Data Loading & Cleaning
- Loaded the CSV file using `pandas`
- Checked for missing values and duplicates
- Encoded categorical variables for easier analysis
- Handled skewed distributions and removed irrelevant outliers

### 2. 📈 Univariate Analysis
- Count plots to show the balance between insured and uninsured individuals
- Histograms of age distribution, segregated by gender and region
- Pie charts to analyze region codes and driving license ownership

### 3. 🔄 Bivariate & Multivariate Analysis
- Cross-tabulation of vehicle damage with insurance status
- Age vs. Insurance: Distribution of age groups likely to be insured
- Heatmaps of correlations to understand variable interactions
- Insurance purchase probability based on previous insurance, gender, and region

---

## 🧠 Key Insights & Business Recommendations

### Demographic Insights:
- **Age Impact**: Individuals between **35 to 55 years** are more likely to purchase insurance.
- **Gender**: Male and female customers show similar likelihoods, indicating a neutral influence.
- **Region**: Some urban regions show higher insurance conversion, which may relate to accessibility and awareness.

### Behavioral Trends:
- **Vehicle Damage**: A **strong positive correlation** exists between vehicle damage history and insurance purchase. People with damaged vehicles are significantly more likely to get insured.
- **Driving License**: Nearly all customers with insurance had a valid driving license, reinforcing its importance in risk assessment.
- **Previously Insured**: Customers previously insured tend to buy again — loyalty and renewal patterns can be leveraged by companies.

### Business Recommendations:
- Launch targeted campaigns for customers aged **35-55** with **vehicle damage history**.
- Focus outreach on **urban and semi-urban regions** with low insurance coverage but high vehicle density.
- Offer renewal incentives to customers previously insured to improve retention.
- Use data-driven risk profiling to streamline policy approval processes and reduce fraud.

---

## 🔍 How to Run This Project

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/vehicle-insurance-eda.git
cd vehicle-insurance-eda
```

### 2. Install Required Libraries
```bash
pip install pandas numpy matplotlib seaborn
```

### 3. Launch the Notebook
```bash
jupyter notebook PFA(Mini_Project).ipynb
```

---

## 📌 Final Takeaway

By analyzing this vehicle insurance dataset, we understand how **simple demographic and behavioral data** can guide profitable business strategies. The EDA not only reveals **who** is more likely to buy insurance, but also **why**, enabling smarter and more personalized service delivery in the insurance industry.

---

## 📬 Contact

- 👩‍💻**Author:** Manya Ghavri 
- 📧**Email:** manyaghavri3211@gmail.com 
- 🌐**GitHub:** [github.com/yourprofile](https://github.com/yourprofile)
- 🔗**Linkedin:** [Linkedin_link](https://www.linkedin.com/in/manya-ghavri-b00773310/)

---

