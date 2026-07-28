# 🏥 Emergency Hospital Room Analytics

## 📌 Project Overview

Emergency departments generate a large volume of patient data every day. Analyzing this data helps hospitals improve operational efficiency, reduce patient waiting times, optimize staff allocation, and enhance patient satisfaction.

This project performs **Exploratory Data Analysis (EDA)** on an Emergency Room dataset using **Python, NumPy, Pandas, Matplotlib, and Seaborn** to uncover meaningful healthcare insights and support data-driven decision-making.

---

## 🎯 Objectives

- Clean and preprocess emergency room data.
- Perform exploratory data analysis (EDA).
- Analyze patient volume trends.
- Evaluate average waiting time.
- Measure admission rates.
- Analyze department performance.
- Study doctor workload and bed occupancy.
- Examine patient satisfaction.
- Generate actionable business insights through data visualization.

---

## 🛠️ Tech Stack

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

---

## 📂 Project Structure

```
Emergency-Hospital-Room-Analytics
│
├── Dataset
│   └── Hospital Emergency Room Data.csv
│
├── Jupyter Notebook
│   └── Emergency_Hospital_Analytics.ipynb
│
├── Images
│   ├── Patient_Volume.png
│   ├── Waiting_Time.png
│   ├── Admission_Rate.png
│   ├── Department_Analysis.png
│   ├── Age_Distribution.png
│   ├── Satisfaction.png
│   ├── Doctor_Workload.png
│   ├── Shift_Analysis.png
│   └── Correlation_Heatmap.png
│
├── README.md
├── requirements.txt
└── LICENSE
```

---

# 📊 Dataset Information

The dataset contains emergency room patient records, including:

- Patient ID
- Age
- Gender
- Race
- Admission Date
- Admission Time
- Department Referral
- Patient Wait Time
- Admission Status
- Satisfaction Score
- Other healthcare-related attributes

---

# 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed using **Pandas**:

- Removed duplicate records.
- Handled missing values.
- Converted date and time columns into datetime format.
- Standardized column names.
- Corrected data types.
- Removed unnecessary columns.
- Created new analytical features for healthcare analysis.

---

# ⚙️ Feature Engineering

New features were created to improve analysis:

- Year
- Month
- Day
- Weekday
- Hour
- Quarter
- Shift (Morning, Afternoon, Evening, Night)
- Weekend Indicator
- Age Group
- Waiting Time Category

---

# 📈 Exploratory Data Analysis (EDA)

The notebook includes detailed analysis of:

### Patient Analysis

- Daily Patient Volume
- Monthly Patient Trend
- Weekly Patient Trend
- Hourly Patient Arrivals
- Shift-wise Patient Distribution

### Waiting Time Analysis

- Average Waiting Time
- Waiting Time Distribution
- Department-wise Waiting Time

### Admission Analysis

- Admission Rate
- Admitted vs Non-Admitted Patients

### Department Analysis

- Department Referral Distribution
- Department Performance
- Doctor Workload

### Patient Demographics

- Age Distribution
- Gender Distribution
- Race Distribution

### Patient Satisfaction

- Satisfaction Score Distribution
- Satisfaction vs Waiting Time

### Statistical Analysis

- Descriptive Statistics
- Correlation Analysis
- Distribution Analysis
- Outlier Detection

---

# 📊 Visualizations

The project contains multiple professional visualizations, including:

- 📈 Patient Volume Trend
- 📅 Monthly Patient Trend
- ⏰ Hourly Patient Arrivals
- ⌛ Waiting Time Distribution
- 🏥 Department Performance
- 🩺 Doctor Workload
- 🛏️ Admission Rate
- 😊 Patient Satisfaction Analysis
- 👥 Age Distribution
- 🌙 Shift Analysis
- 🔥 Correlation Heatmap

---

# 💡 Key Insights

- Patient arrivals are highest during specific peak hours.
- Average waiting time varies significantly across departments.
- Certain departments experience heavier patient loads than others.
- Longer waiting times are associated with lower patient satisfaction.
- Adults represent the largest proportion of emergency room visits.
- Patient arrival patterns can be used to optimize staffing schedules.
- Department workload analysis helps improve resource allocation.

---

# 📌 Business Recommendations

- Increase staffing during peak patient hours.
- Reduce waiting time in high-demand departments.
- Allocate resources based on patient volume trends.
- Monitor patient satisfaction regularly.
- Optimize shift scheduling using historical patient arrival data.
- Use data-driven decision-making to improve hospital efficiency.

---

# 🚀 How to Run the Project

### Clone the repository

```bash
git clone https://github.com/semraj2027/Emergency-Hospital-Room-Analytics.git
```

### Navigate to the project folder

```bash
cd Emergency-Hospital-Room-Analytics
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Open

```
Emergency_Hospital_Analytics.ipynb
```

---

# 📦 Requirements

Install the required Python libraries:

```bash
pip install numpy pandas matplotlib seaborn jupyter
```

Or install everything using:

```bash
pip install -r requirements.txt
```

---

# 🎯 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Healthcare Analytics
- Statistical Analysis
- Data Visualization
- Business Insight Generation
- Python Programming

---

# 🚀 Future Enhancements

- Interactive Power BI Dashboard
- Streamlit Web Application
- SQL Database Integration
- Machine Learning for Patient Admission Prediction
- Waiting Time Prediction Model
- Real-Time Healthcare Analytics Dashboard

---

# 👨‍💻 Author

**Semraj**

B.Tech – Metallurgical & Materials Engineering  
National Institute of Technology (NIT) Raipur

**GitHub:** https://github.com/semraj2027

---

# 📄 License

This project is licensed under the MIT License.

---

## ⭐ Support

If you found this project useful:

- ⭐ Star this repository
- 🍴 Fork this repository
- 💡 Share your feedback
- 🤝 Feel free to contribute

---

**If you like this project, don't forget to ⭐ star the repository!**
