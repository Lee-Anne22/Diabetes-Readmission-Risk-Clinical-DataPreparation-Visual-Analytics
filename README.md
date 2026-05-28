# Diabetes-Readmission-Risk-Clinical-DataPreparation-Visual-Analytics
Here is a polished, consulting‑ready, GitHub‑formatted **README** for your **SS3 Diabetes Readmission Analysis** project.  
It is structured for professional audiences (McKinsey, BCG, Bain, data science recruiters) and written in clean Markdown.

---

# **Diabetes Readmission Analysis – Clinical Data Exploration & Ethical Interpretation**  
*A visual analytics and responsible data‑science case study*

---

## **Overview**
This project explores a large clinical dataset representing **10 years of inpatient diabetes care** across **130 US hospitals**. The analytical focus is on **early hospital readmission** (within 30 days), a key indicator of healthcare quality, patient safety, and care effectiveness.

The project spans:

- Clinical data inspection and preparation  
- Feature creation for analytical clarity  
- Visual exploration of readmission patterns  
- Ethical reflection on working with sensitive health data (Not Included on Github)

---

## 📂 **Project Structure**
```plaintext
📁 diabetes-readmission-analysis
│
├── Diabetes_Readmission_Risk.ipynb
|
└── README.md
```

---

## **Datasets Used**

### **1. diabetic_data.csv (Primary Clinical Dataset)**
A large, encounter‑level dataset containing:

- Patient demographics  
- Admission and discharge details  
- Laboratory results  
- Medication counts  
- Diagnoses  
- Readmission outcomes  

Each row represents a hospital encounter for a patient diagnosed with diabetes.

### **2. IDS_mapping.csv (Metadata & Codebook)**
A supporting dataset providing:

- Attribute descriptions  
- Category mappings  
- Clinical code interpretations  

Used to ensure accurate understanding and responsible interpretation of clinical variables.

### **3.cleaned_diabetes_data.csv (cleaned dataset)**
A supporting dataset providing:

---

## **Key Components**

---

## **Part 1 — Data Understanding & Analytical Preparation**

### **1. Initial Inspection**
- Loaded the clinical dataset into a Pandas DataFrame.  
- Displayed the first five rows, dataset structure, and column list.  
- Reported dataset dimensions (rows × columns).

### **2. Data Cleaning & Preparation**
Focused on variables required for visual analysis:

- **readmitted**  
- **admission_type**  
- **medical_specialty**  
- **num_medications**  
- **time_in_hospital**  
- **age**  
- **gender**  
- **race**  
- **encounter count per patient**

Preparation steps included:

- Identifying and handling missing or invalid categories  
- Correcting data types  
- Mapping `admission_type_id` to labelled categories  
- Reviewing and simplifying age‑group categories where appropriate  
- Creating a new variable for **number of encounters per patient**  

The goal was to produce a **clean, focused analytical dataset** suitable for visual exploration.

---

## **Part 2 — Visual Analysis & Interpretation**

Eight analytical questions guided the visual exploration:

### **1. Distribution of Readmission Categories**
Focus on early readmission (within 30 days).

### **2. Readmission by Admission Type**
Identifying admission types associated with higher early‑readmission proportions.

### **3. Readmission Across Age Group & Gender**
Exploring demographic patterns.

### **4. Time in Hospital vs. Readmission Category**
Assessing whether early‑readmitted patients have different lengths of stay.

### **5. Number of Medications by Readmission Category**
Understanding treatment intensity.

### **6. Treatment Intensity Across Race & Readmission Category**
Average medication counts by racial group and readmission outcome.

### **7. Early Readmission by Number of Encounters per Patient**
Based on **unique patients**, not encounters.

### **8. Most Frequent Medical Specialties**
Identifying which specialties most commonly admit diabetic patients  
(excluding unknown/invalid categories where justified).

---

## **Technologies Used**
- Python  
- Pandas  
- NumPy  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## **Skills Demonstrated**
- Clinical data understanding  
- Data cleaning and preparation  
- Feature engineering  
- Visual analytics  
- Interpretation of healthcare patterns  
- Ethical reasoning in data science  
- Responsible communication of sensitive findings  

---

## **Potential Extensions**
- Predictive modelling for early readmission  
- Risk‑stratification dashboards for clinicians  
- Fairness and bias audits across demographic groups  
- Survival analysis or time‑to‑event modelling  

---
