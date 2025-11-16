## **Machine Learning Project**

### **Team Members**
- **Srishti Lamba - 202518003**  
- **Harsh Patel - 202518011**  
- **Meet Gandhi - 202518023**  
- **Nikita Sharma - 202518038**  
- **Sanil Shah - 202518060**

---

## **Project Objectives**

This project aims to analyze UK road accident data and build machine learning models to understand and predict accident outcomes. The core objectives are:

### **Problem Statement 1 - Accident Severity Classification**
Developed a machine learning model to classify accident severity (Slight, Serious/Fatal) using environmental, vehicle, driver, and road-related attributes. This helps identify high-risk conditions and supports preventive safety measures.

### **Problem Statement 2 - Infrastructure Safety Optimization**
Analyzed accident patterns to identify which infrastructure factors, such as junction types, speed limits, and lighting contribute most to severe collisions. These insights help urban planners prioritize high-impact road improvements.

### **Problem Statement 3 - Collision Risk Prediction**
Built an explainable collision-risk prediction model to support proactive safety planning and early warning systems.

---

## **Dataset Description**

This project uses the **UK Road Accident & Safety Data (2024)** published by the UK Department for Transport.

**Source:**  
[Road Accidents & Safety Data – data.gov.uk](https://www.data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-accidents-safety-data)

The dataset consists of detailed, police-reported road traffic accidents across Great Britain, including accident-level, vehicle-level, and casualty-level information.

---

## **Dataset Used in This Project**

Dataset file: **`Final_Meet.csv`**

- **Rows:** 89,019  
- **Columns:** 23  

---

## **Feature Description**

### **Accident-Level Attributes**
- Accident_Index  
- Accident Date  
- Day_of_Week  
- Accident_Severity  
- Number_of_Casualties  
- Number_of_Vehicles  
- Time  

### **Road & Environmental Attributes**
- Junction_Control  
- Junction_Detail  
- Road_Type  
- Speed_limit  
- Road_Surface_Conditions  
- Weather_Conditions  
- Light_Conditions  
- Carriageway_Hazards  
- Urban_or_Rural_Area  

### **Location Coordinates**
- Latitude  
- Longitude  
- Local_Authority_(District)  
- Police_Force  

### **Vehicle & Driver Attributes**
- Vehicle_Type  
- Driver_Gender  
- Driver_Age  

---

## **Why This Dataset?**

- Official government dataset  
- Reliable, standardized data collection  
- Rich set of environmental, vehicle, and driver variables  
- Ideal for classification, risk prediction, and pattern discovery  

---

## **Technology Used (Tech Stack)**

### **Programming & Core Tools**
- Python 3.10+  
- Jupyter Notebook  

### **Data Handling**
- pandas  
- numpy  

### **Visualization**
- matplotlib  
- seaborn  

### **Machine Learning**
- scikit-learn  
- XGBoost  
- CatBoost  

### **Version Control**
- Git  
- GitHub  

---

## 📂 **Project Structure**

```text
📁 Zeta-X-_Model_Submission
│
├── 📂 DataDecoding/
│   ├── Decoding_File.ipynb              
│   ├── Final.csv
│   ├── dft-road-casualty-statistics-collision-2024.csv
│   ├── dft-road-casualty-statistics-vehicle-2024.csv                  
│
├── 📂 EDA/
│   ├── final_eda.ipynb                  
│   ├── uk_accident_eda.ipynb            
│
├── 📂 Model/
│   ├── Model-Bagging.ipynb              
│   ├── Model-LightGBM_New.ipynb         
│   ├── Model-XGBoost.ipynb              
│
├── 📂 Problem-Statement1/
│   ├── Accident_Severity_Classification.ipynb
│
├── 📂 Problem-Statement2/
│   ├── Conclusion_Problem2.ipynb           
│   ├── problem_statement2_models.ipynb     
│
├── 📂 Problem-Statement3/
│   ├── Collision_Risk_XGBClassifier.ipynb        
│
├── 📄 README.md
│
└── 📄 REPORT.docx                             
