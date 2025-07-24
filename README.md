🍷 Outlier Detection using Five Number Summary & Box Plot | Wine Dataset

This project demonstrates how to detect outliers in a dataset using the Five Number Summary and Box Plot techniques. Outlier detection is a crucial step in data cleaning and EDA (Exploratory Data Analysis) to ensure robust model performance.


---

📁 Dataset: Wine

Source: sklearn.datasets.load_wine()

Samples: 178 wines

Classes: 3 (Wine types)

Features: 13 chemical analysis features (e.g., alcohol, ash, malic_acid, proline, etc.)



---

📊 Techniques Used

✅ Five Number Summary

For each feature:

Minimum

1st Quartile (Q1)

Median (Q2)

3rd Quartile (Q3)

Maximum


✅ IQR (Interquartile Range) Method

\text{IQR} = Q3 - Q1 \\
\text{Lower Bound} = Q1 - 1.5 \times \text{IQR} \\
\text{Upper Bound} = Q3 + 1.5 \times \text{IQR}

Any value outside [Lower Bound, Upper Bound] is considered an outlier.


✅ Box Plot Visualization

Helps identify outliers visually across all 13 features.



---

📌 Project Workflow

1. 📥 Load Wine dataset using sklearn.datasets


2. 📊 Convert it to a Pandas DataFrame


3. 📌 Select numerical features


4. 🔍 Compute Five Number Summary for each


5. 💡 Detect outliers using IQR bounds


6. 📈 Visualize distributions and outliers with Seaborn & Matplotlib




---

🛠️ Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn



---

🚀 How to Run

1. Open this notebook in Google Colab


2. Run all cells sequentially


3. Scroll to boxplots and outlier reports for insights




---

📚 Learning Outcomes

Understand how outliers affect machine learning

Apply the IQR method for robust detection

Visualize outliers across multiple features

Prepare clean data for modeling



---

✍️ Author

Divyanshu Jyotishi 
🔍 M.L learner | 📱 ML Projects from Phone
Focused on mastering AI & ML through practical projects
