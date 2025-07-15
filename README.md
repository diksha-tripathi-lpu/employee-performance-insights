# 🧠 Employee Performance Segmentation for HR Insights

A complete Machine Learning + Power BI project that segments employees based on key productivity indicators. This project empowers HR departments with actionable insights by identifying top performers and employees who need support — using clustering and classification techniques with visual dashboards.

---

## 📌 Objective

Segment employees based on:
- ✅ Task Completion Efficiency
- ✅ Attendance Regularity
- ✅ Feedback Rating
- ✅ Length of Service (in Years)

Using unsupervised learning (KMeans) and supervised classification (Random Forest), this project creates a labeled dataset and delivers HR-friendly dashboards for better workforce planning.

---

## 📁 Dataset

A custom-generated dataset with 1000 entries containing:
- Employee ID
- Department
- Team
- Task Completion Efficiency
- Attendance Regularity
- Feedback Rating (1–5)
- Length of Service (Years)
---

## 🧠 Project Workflow

| Step | Description |
|------|-------------|
| **1. Data Preprocessing** | Removed duplicates, checked for nulls, scaled numeric features |
| **2. EDA** | Used Seaborn and Matplotlib to explore data patterns and correlations |
| **3. Feature Engineering** | Created `Avg_Performance_Score` and `High_Performer` label |
| **4. Clustering** | Used KMeans (k=4) to segment employees into performance clusters |
| **5. Classification** | Trained a Random Forest to predict high performers |
| **6. Visualization** | Designed a Power BI dashboard to present key HR insights |
| **7. Deployment** | Shared on GitHub & LinkedIn with clean code and documentation |


---

## 📊 Power BI Dashboard

The Power BI dashboard brings the insights to life through these components:

| 📈 Visual | 📋 Description |
|----------|----------------|
| **Card: Count of Employee** | Displays total number of employees (1000) |
| **Card: Avg_Attendance** | Average attendance across employees |
| **Card: Avg_Performance** | Average overall performance score |
| **Card: Task_Completion_Efficiency** | Average task efficiency |
| **Card: Avg_Feedback_Rating** | Mean feedback score (1–5) |
| **Bar Chart: Count of Department by Performance_Cluster** | Shows how employees in each department fall into clusters |
| **Bar Chart: Count of Attendance_Regularity by Team** | Compares attendance patterns across teams |
| **Line Chart: Average Task Completion by Department** | Department-wise task completion comparison |
| **Pie Chart: Avg Length of Service by Department** | Average years of service per department (with % shares) |
| **Line + Bar Chart: Feedback Rating & Length of Service by Team** | Combines team-wise feedback and experience levels |
| **Slicer: Team Filter** | Lets HR filter data by team (Alpha to Zeta) |

📂 File: `HR_Performance_Dashboard.pbix`

---

## 🧪 ML Techniques Used

| Type | Method | Purpose |
|------|--------|---------|
| Clustering | KMeans (k=4) | Group employees based on performance metrics |
| Classification | Random Forest | Predict high-performing employees |
| Feature Engineering | Avg_Performance_Score | Weighted score of task, attendance, and feedback |

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `employee_performance_data.csv` | Original dataset with raw values |
| `employee_data_with_clusters_and_labels.csv` | Final dataset with added cluster and label columns |
| `Final_Employee_Performance_Segmentation.ipynb` | Full Python workflow in Jupyter Notebook |
| `HR_Performance_Dashboard.pbix` | Power BI dashboard file |
| `README.md` | Complete project documentation |

---

## 📈 Key Insights

- Task Completion Efficiency drops significantly in the R&D department.
- Teams like Epsilon and Delta had the most variation in feedback and service years.
- Top performers were distributed across multiple teams, not limited to one department.

---

## 👩‍💻 Author

**Diksha Tripathi**  
B.Tech CSE | Lovely Professional University  
🔗 [LinkedIn](https://www.linkedin.com/in/diksha-tripathi-0024a1230)  
🔗 [GitHub](https://github.com/diksha-tripathi-lpu)

---

## 🏷️ Tags

`#MachineLearning` `#Clustering` `#RandomForest` `#PowerBI`  
`#DataVisualization` `#HRAnalytics` `#PythonProject` `#GitHubPortfolio`

---

## ⭐ Found this helpful? Star the repo and connect on LinkedIn!
