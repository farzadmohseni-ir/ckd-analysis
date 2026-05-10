# ckd-analysis
Chronic Kidney Disease dataset analysis for Data Mining course.


# 🧪 Data Mining Assignment 01  
## 🏥 Chronic Kidney Disease (CKD) Analysis  

---

## 🎓 Course Information  
📘 **Course:** Data Mining: Models, Algorithms, and Applications  
👨‍🏫 **Instructor:** Dr. Ahmadi  
🏫 **University:** Amirkabir University of Technology (Tehran Polytechnic)  

# 📌 Problem Description  

🧪 Select the **Chronic Kidney Disease (CKD)** dataset from the  
**UCI Machine Learning Repository** and provide a brief description of it.



# 🧩 Assignment Tasks  

## 🔧 (A) Data Preparation  

- Handle **missing values** and **noisy data**  
- Apply **data standardization** using **three different methods**



## 📉 (B) Feature Reduction  

Apply the following feature selection methods:

- 🔹 Filter Method  
- 🔹 Forward Selection  
- 🔹 Backward Elimination  
- 🔹 Hybrid Method (Forward + Backward)  
  - Explain how parameters **L** and **R** are selected  

📊 For each method:

- Present the selected features  
- Analyze and compare results in terms of:
  - Number of features  
  - Quality (performance)

📌 When needed, use **K-Nearest Neighbors (KNN)** for classification.



## 🧠 (C) Principal Component Analysis (PCA)  

- Apply PCA on the dataset  
- Determine how much variance each component explains  
- Plot the **Scree Plot**  
- Select the optimal number of components with justification  



## 🏁 (D) Final Evaluation  

Based on accuracy:

- Compare all methods:
  - Filter  
  - Forward  
  - Backward  
  - Hybrid  
  - PCA  

🎯 Determine which method provides the **best performance compared to using all features**.

---

# 📊 Dataset Overview  

- 📦 **Total Records:** 400  
- 📦 **Total Columns:** 26 (including ID and target)  
- 🆔 **ID Column:** Unique identifier (not used as a feature)  
- 📥 **Input Features:** 24  
- 🎯 **Target Variable:** `classification` (ckd / notckd)  
- 🔢 **Numerical Features:** 11  
- 🔤 **Nominal Features:** 14  
- ⚠️ **Missing Values:** Yes  

🔗 **Dataset Link:**  
https://archive.ics.uci.edu/dataset/336/chronic+kidney+disease  

---

# 🧾 Feature Names and Descriptions  

| No. | Attribute | Type | Meaning | Description |
|-----|----------|------|---------|-------------|
| 0 | id | Nominal | Record ID | Unique identifier for each record |
| 1 | age | Numerical | Age | Age in years |
| 2 | bp | Numerical | Blood Pressure | Blood pressure in mm/Hg |
| 3 | sg | Nominal | Specific Gravity | Values: 1.005, 1.010, 1.015, 1.020, 1.025 |
| 4 | al | Nominal | Albumin | Values: 0, 1, 2, 3, 4, 5 |
| 5 | su | Nominal | Sugar | Values: 0, 1, 2, 3, 4, 5 |
| 6 | rbc | Nominal | Red Blood Cells | Values: normal, abnormal |
| 7 | pc | Nominal | Pus Cell | Values: normal, abnormal |
| 8 | pcc | Nominal | Pus Cell Clumps | Values: present, notpresent |
| 9 | ba | Nominal | Bacteria | Values: present, notpresent |
| 10 | bgr | Numerical | Blood Glucose Random | Measured in mgs/dl |
| 11 | bu | Numerical | Blood Urea | Measured in mgs/dl |
| 12 | sc | Numerical | Serum Creatinine | Measured in mgs/dl |
| 13 | sod | Numerical | Sodium | Measured in mEq/L |
| 14 | pot | Numerical | Potassium | Measured in mEq/L |
| 15 | hemo | Numerical | Hemoglobin | Measured in gms |
| 16 | pcv | Numerical | Packed Cell Volume | Packed cell volume |
| 17 | wc | Numerical | White Blood Cell Count | Measured in cells/cumm |
| 18 | rc | Numerical | Red Blood Cell Count | Measured in millions/cmm |
| 19 | htn | Nominal | Hypertension | Values: yes, no |
| 20 | dm | Nominal | Diabetes Mellitus | Values: yes, no |
| 21 | cad | Nominal | Coronary Artery Disease | Values: yes, no |
| 22 | appet | Nominal | Appetite | Values: good, poor |
| 23 | pe | Nominal | Pedal Edema | Values: yes, no |
| 24 | ane | Nominal | Anemia | Values: yes, no |
| 25 | classification | Nominal | Class Label | Values: ckd (Chronic Kidney Disease), notckd (Not CKD) |

---
