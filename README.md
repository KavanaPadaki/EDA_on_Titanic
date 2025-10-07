## Y-Data Profiling: Titanic Dataset

This section summarizes key insights from profiling the target variable `Survived` in the Titanic dataset. The goal is to understand class distribution, categorical influences, and survival patterns that inform model design and evaluation.

---

### Target Variable: `Survived`

- **Type**: Binary categorical (`0` = Did not survive, `1` = Survived)
- **Class Imbalance**:  
  - Over **500 passengers did not survive**, indicating a skewed distribution.
  - Important for choosing appropriate metrics (e.g., precision, recall) and resampling strategies.

---

###  Categorical Insights Related to Survival

- **Pclass**  
  - Most passengers were in **3rd class**, followed by **1st**, then **2nd**.  
  - Lower-class passengers had **lower survival rates**, reflecting socioeconomic impact.

- **Sex**  
  - There were significantly more **males** than females.  
  - **Females had much higher survival rates**, suggesting prioritization during evacuation.

- **Embarked**  
  - The vast majority of passengers boarded at **Southampton ('S')**.  
  - Embarkation point may correlate with class and survival odds.

- **SibSp & Parch**  
  - Most passengers **traveled alone** (no siblings/spouses or parents/children aboard).  
  - Solo travelers had **lower survival odds** compared to those with family.

---

###  Why This Matters

Understanding the target variable helps:
- Choose the right **model type** and **evaluation metrics**
- Detect **biases** and **imbalances** in the data
- Inform **feature engineering** and **group-wise analysis**

