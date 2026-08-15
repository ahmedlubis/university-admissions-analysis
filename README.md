# 🎓 University Admissions Analysis

An exploratory data analysis project examining **university admissions, student characteristics, academic performance, and enrollment outcomes** to identify patterns in applicant profiles and admission decisions.

## 🎯 Problem

Universities receive applicants with different academic backgrounds, test scores, extracurricular experiences, and demographic characteristics.

This project explores:

* What characteristics are associated with admission outcomes?
* How do academic scores differ between admitted and rejected applicants?
* Which applicant characteristics show the strongest relationship with admission?
* What patterns can be observed across student profiles?
* Can exploratory analysis provide useful insights for understanding the admissions process?

## 📊 Dataset

The project uses a university admissions dataset containing information about student applications, academic performance, and admission outcomes.

### Main Variables

| Variable            | Description                        |
| ------------------- | ---------------------------------- |
| `GRE Score`         | Graduate Record Examination score  |
| `TOEFL Score`       | English proficiency test score     |
| `University Rating` | University rating                  |
| `SOP`               | Statement of Purpose strength      |
| `LOR`               | Letter of Recommendation strength  |
| `CGPA`              | Undergraduate GPA / CGPA           |
| `Research`          | Research experience indicator      |
| `Chance of Admit`   | Estimated probability of admission |

The dataset contains **500 student application records**.

## 🔬 Method

The analysis follows an exploratory data-analysis workflow.

### 1. Data Preparation

The dataset is prepared by:

* Inspecting data types and structure
* Checking for missing values
* Removing unnecessary index columns
* Renaming variables where appropriate
* Checking numerical distributions
* Identifying potential outliers

### 2. Exploratory Data Analysis

The analysis examines relationships between admission probability and:

* GRE score
* TOEFL score
* CGPA
* University rating
* Statement of Purpose
* Letter of Recommendation
* Research experience

### 3. Correlation Analysis

Correlation analysis is used to identify variables with stronger linear relationships with `Chance of Admit`.

### 4. Group Comparison

Applicant characteristics are compared across different levels of admission probability and research experience.

The analysis is primarily **descriptive and exploratory**, rather than a predictive admissions model.

## 📈 Results

### 1. Academic Performance Is Strongly Associated with Admission Probability

Among the academic variables, **CGPA and GRE score** show strong positive relationships with `Chance of Admit`.

Students with stronger academic performance generally have higher estimated admission probabilities.

### 2. GRE and TOEFL Scores Show Positive Relationships

Higher standardized test scores tend to be associated with higher admission probabilities.

This suggests that standardized academic performance is an important characteristic within the analyzed dataset.

### 3. Research Experience Is Associated with Higher Admission Probability

Applicants with research experience generally show higher admission probabilities than applicants without research experience.

However, this is a descriptive relationship and should not be interpreted as proof that research experience directly causes admission.

### 4. Statement of Purpose and Recommendation Scores

SOP and LOR ratings also show positive relationships with admission probability, although their associations are weaker than the strongest academic indicators.

### 5. University Rating

Applicants targeting higher-rated universities tend to have stronger academic profiles and higher estimated admission probabilities.

This suggests that university selection and applicant characteristics are closely related within the dataset.

## 📊 Visualization

### Correlation Heatmap

![Correlation Heatmap](insight1.png)

The correlation heatmap provides an overview of the relationships between academic characteristics, application attributes, and admission probability.

### Academic Performance vs. Admission Probability

![CGPA vs Admission Probability](insight2.png)

The relationship between CGPA and admission probability demonstrates the strong positive association between undergraduate academic performance and the estimated chance of admission.

### Research Experience

![Research Experience](insight3.png)

The comparison highlights differences in admission probability between applicants with and without research experience.

### Recommended Additional Visualizations

For a stronger portfolio presentation, I would include:

* GRE vs. Chance of Admit
* CGPA vs. Chance of Admit
* TOEFL vs. Chance of Admit
* Research vs. Chance of Admit
* Admission probability distribution
* Correlation heatmap

## 💡 Conclusion

The analysis identifies several characteristics that are strongly associated with university admission probability.

### Key Takeaways

**1. Academic performance matters.**

CGPA and standardized test scores show strong positive relationships with admission probability.

**2. Research experience is an important applicant characteristic.**

Applicants with research experience tend to have higher estimated admission probabilities in the dataset.

**3. Application components also matter.**

SOP and LOR ratings show positive relationships with admission probability, although their relationships are less pronounced than some academic indicators.

**4. Applicant characteristics are interconnected.**

Students with stronger academic profiles often exhibit stronger application characteristics across multiple variables.

Overall, the analysis suggests that **academic performance and broader application quality are important characteristics associated with admission outcomes in the dataset**.

> **Important:** The dataset contains estimated admission probabilities rather than confirmed admission decisions. Therefore, the results should be interpreted as associations within the dataset rather than causal evidence about real university admissions.

## ⚠️ Limitations

This analysis has several limitations:

* The dataset contains **500 observations**, limiting generalization.
* `Chance of Admit` represents an estimated probability rather than a confirmed admission outcome.
* The dataset may not represent a particular university or admissions system.
* Correlation does not establish causation.
* The analysis does not account for all factors that may influence real admissions decisions.

### Future Improvements

A stronger version of the project could include:

* Multiple linear regression
* Logistic regression using an admission threshold
* Random Forest classification
* Feature importance
* Cross-validation
* ROC-AUC
* SHAP explanations
* University-level comparisons

## 🛠️ Technologies

* **Python**
* **Pandas** — data manipulation
* **NumPy** — numerical analysis
* **Matplotlib** — visualization
* **Seaborn** — statistical visualization
* **Jupyter Notebook**
* **Exploratory Data Analysis**
* **Correlation Analysis**
* **Statistical Analysis**

### Methods

`EDA` `Correlation Analysis` `Data Visualization` `Statistical Analysis` `Feature Analysis`

## 📁 Repository Structure

```text
university-admissions-analysis/
│
├── data/
│   └── admission.csv
│
├── figures/
│   ├── correlation-heatmap.png
│   ├── cgpa-admission.png
│   ├── gre-admission.png
│   └── research-experience.png
│
├── university-admissions-analysis.ipynb
└── README.md
```

## 📌 Topics

`Python` `Pandas` `EDA` `Data Analysis` `Data Visualization` `University Admissions` `Student Analytics` `Statistics` `Seaborn` `Matplotlib`
