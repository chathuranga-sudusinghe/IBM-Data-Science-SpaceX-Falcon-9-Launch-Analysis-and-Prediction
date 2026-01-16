# 🚀 SpaceX Falcon 9 Launch Success Prediction
IBM Data Science Capstone Project

## 📌 Project Overview
This project is the final capstone of the **IBM Data Science Professional Certificate**.  
The objective is to analyze historical **SpaceX Falcon 9 launch data** and build machine learning models to **predict the success of first-stage landings**.

Successful recovery of the Falcon 9 first stage plays a critical role in reducing launch costs. This project applies end-to-end data science techniques to uncover insights and build predictive models that support data-driven decision making.

---

## 🎯 Objectives
- Analyze historical Falcon 9 launch data
- Identify factors affecting launch success
- Perform exploratory data analysis (EDA) using visualization and SQL
- Build interactive maps and dashboards
- Develop and evaluate classification models to predict launch success

---

## 🗂️ Project Structure
├── data/
│ ├── spacex_launch_data.csv
│ └── spacex_web_scraped.csv
│
├── notebooks/
│ ├── 01_Data_Collection_API.ipynb
│ ├── 02_Data_Collection_Web_Scraping.ipynb
│ ├── 03_Data_Wrangling.ipynb
│ ├── 04_EDA_Visualization.ipynb
│ ├── 05_EDA_SQL.ipynb
│ ├── 06_Folium_Maps.ipynb
│ ├── 07_Plotly_Dash_App.ipynb
│ └── 08_Predictive_Analysis.ipynb
│
├── dashboard/
│ └── app.py
│
├── presentation/
│ └── IBM_Data_Science_Capstone_Final.pdf
│
└── README.md



---

## 🛠️ Tools & Technologies
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Databases:** SQL (SQLite)  
- **Visualization:** Matplotlib, Seaborn, Plotly, Folium  
- **Dashboard:** Plotly Dash  
- **Environment:** Jupyter Notebook  

---

## 🔍 Methodology

### 1️⃣ Data Collection
- SpaceX REST API for launch and rocket data
- Web scraping (Wikipedia) for historical launch records

### 2️⃣ Data Wrangling
- Handling missing values
- Encoding categorical features
- Feature selection and transformation
- Train-test split

### 3️⃣ Exploratory Data Analysis (EDA)
- Payload mass vs launch success
- Launch site vs success rate
- Orbit type vs success rate
- Yearly launch success trends

### 4️⃣ SQL Analysis
- Aggregate payload statistics
- Filter launches by site and year
- Rank landing outcomes
- Identify success and failure patterns

### 5️⃣ Interactive Visual Analytics
- **Folium:** Interactive maps of launch sites and landing outcomes
- **Plotly Dash:** Interactive dashboard for launch success analysis

### 6️⃣ Predictive Analysis
Classification models used:
- Logistic Regression
- Decision Tree
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

Models were evaluated using accuracy and confusion matrices.

---

## 📊 Results
- **Decision Tree Classifier** achieved the highest accuracy
- Payload mass and orbit type significantly influence success
- Certain launch sites consistently show higher success rates
- Machine learning models effectively predict Falcon 9 landing outcomes

---

## ✅ Conclusion
This project demonstrates a complete **end-to-end data science workflow**, from raw data collection to predictive modeling.  
The results highlight how data science and machine learning can support operational decision-making in aerospace missions.

---

## 📎 References
- SpaceX API: https://github.com/r-spacex/SpaceX-API
- Wikipedia: https://en.wikipedia.org/wiki/List_of_Falcon_9_and_Falcon_Heavy_launches
- IBM Data Science Professional Certificate – Coursera

---

## 👤 Author
**Chathuranga Indrajith Sudusinghe**  
IBM Data Science Professional Certificate Graduate  

