📊 Learning Disorder Statistical Analysis

🧠 Objective
This project aims to analyze behavioral, psychological, and lifestyle factors associated with ADHD using statistical techniques. The goal is to identify patterns that may help in early understanding of learning disorders.

📁 Dataset
Source: Kaggle
The dataset includes variables such as:
Age, Gender, Education Stage
Inattention, Hyperactivity, Impulsivity Scores
Sleep Hours and Screen Time
Family History and Comorbid Conditions
Academic Performance
ADHD Diagnosis

🛠 Tools & Technologies
Python (Pandas, NumPy)
Data Visualization (Matplotlib, Seaborn)
Kaggle Notebook
GitHub

📊 Analysis Performed
Data Cleaning and Preprocessing
Exploratory Data Analysis (EDA)
Correlation Analysis
Chi-Square Test for Association
Visualization of Behavioral Patterns

🔍 Key Insights
Both groups average around 4–4.5 hours of screen time and 7 hours of sleep.

Modeling Tip: These features have low "information gain." If you use them in a machine learning model, they likely won't help the model distinguish between the two classes.

With a p-value of $0.0000977$, there is a statistically significant link between genetics/family history and an ADHD diagnosis.Actionable Step: This should be your "top-tier" feature. If you are building a decision tree or a logistic regression model, this variable will likely have the highest weight.

Students without ADHD consistently score higher (median $\approx 80$) than students with ADHD (median $\approx 75-77$).Variability: The ADHD group shows much higher variance in scores, meaning their academic outcomes are less predictable and more prone to extreme lows.

Medication has almost no effect on scores, acting as a "baseline" control.

ADHD Group: Interestingly, those on Non-stimulants showed slightly better and more stable academic performance in this specific dataset than those on stimulants or no medication at all.

📂 Project Structure

data/
├── raw/ → Original dataset
└── processed/ → Cleaned dataset

notebooks/
└── codes_visuals.ipynb → Analysis notebook

📌 Conclusion

The analysis highlights significant relationships between lifestyle factors and ADHD. These insights can contribute to better awareness and early identification of learning disorders.

💡 About the Project

This project was developed as a beginner-level statistical analysis to apply concepts like correlation, hypothesis testing, and data visualization on real-world data.

👩‍💻 Author

Anusha Sharma
