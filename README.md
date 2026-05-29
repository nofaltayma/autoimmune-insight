# AutoImmune Insight: Patient-Centered Data Analysis for Autoimmune Disease

**Google Data Analytics Certificate — Capstone Project**
**Author:** Tayma Nofal | MBA Healthcare Administration

---

## Project Overview

Autoimmune diseases affect over 50 million Americans, yet patients often wait **3–5 years** for an accurate diagnosis. This project analyzes publicly available health data to identify patterns in autoimmune disease symptoms, diagnosis timelines, treatment outcomes, and lifestyle factors — with the goal of producing actionable insights that help patients better understand their conditions and support earlier, more accurate diagnosis.

---

## Business Task

**How can data analytics improve the patient experience for autoimmune disease sufferers — from symptom onset to diagnosis to lifestyle management?**

Sub-questions:
1. What are the most common symptom patterns preceding an autoimmune diagnosis?
2. Which demographic groups face the longest diagnostic delays?
3. What lifestyle and treatment factors correlate with better quality-of-life outcomes?
4. How can this data be communicated clearly to patients and healthcare providers?

---

## Dataset Sources

| Dataset | Source | Description |
|---|---|---|
| NHANES (National Health and Nutrition Examination Survey) | CDC / data.gov | Demographics, lab results, chronic conditions |
| Medical Expenditure Panel Survey (MEPS) | AHRQ | Treatment costs, healthcare access, diagnosis timelines |
| Autoimmune Disease Patient Survey Data | Kaggle | Self-reported symptoms, diagnosis delays, quality of life |
| NIH All of Us Research Program | NIH | Multi-condition health records (de-identified) |

All datasets are publicly available and de-identified.

---

## Tools Used

| Phase | Tool |
|---|---|
| Data cleaning & preparation | Python (pandas, numpy) |
| Exploratory data analysis | Python (matplotlib, seaborn) |
| Statistical analysis | Python / R |
| Interactive dashboard | Tableau Public |
| Documentation | Jupyter Notebook |
| Version control | GitHub |

---

## Project Structure

```
autoimmune-insight/
│
├── data/
│   ├── raw/                  # Original downloaded datasets
│   └── cleaned/              # Processed, analysis-ready data
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda_symptoms.ipynb
│   ├── 03_diagnosis_delay_analysis.ipynb
│   ├── 04_lifestyle_outcomes.ipynb
│   └── 05_visualizations.ipynb
│
├── visuals/
│   └── charts, exported figures
│
├── dashboard/
│   └── tableau_link.md       # Link to published Tableau dashboard
│
├── reports/
│   └── final_report.pdf      # Executive summary & patient-facing report
│
└── README.md
```

---

## Key Analysis Steps

### 1. Data Cleaning (Python / pandas)
- Merge NHANES and MEPS datasets on anonymized patient IDs
- Handle missing values and standardize condition codes (ICD-10)
- Filter for autoimmune conditions: Lupus, Rheumatoid Arthritis, MS, Hashimoto's, Crohn's, Celiac, Type 1 Diabetes, Psoriasis

### 2. Exploratory Data Analysis
- Symptom frequency analysis: which symptoms appear most often before diagnosis
- Demographic breakdown: age, gender, ethnicity, geography
- Time-to-diagnosis distribution across disease types
- Healthcare access variables (insurance, visits, specialists)

### 3. Diagnosis Delay Analysis
- Calculate average time from first reported symptom to confirmed diagnosis
- Identify factors that correlate with longer delays (misdiagnosis rates, demographics, access)
- Visualize diagnostic journey as a timeline

### 4. Lifestyle & Treatment Outcomes
- Correlate diet, exercise, stress, and sleep data with quality-of-life scores
- Compare outcomes across treatment types (biologics, immunosuppressants, lifestyle-only)
- Identify most impactful lifestyle changes reported by patients

### 5. Patient-Facing Insights
- Translate findings into plain-language summaries
- Create a symptom checklist tool
- Build an interactive Tableau dashboard for patients and providers

---

## Key Findings (Preview)

> *Full findings available in the Jupyter notebooks and final report.*

- **Average diagnosis delay:** 4.5 years from first symptom across all autoimmune conditions
- **Most misdiagnosed conditions:** Lupus (avg. 6 years), MS (avg. 5 years)
- **Top pre-diagnosis symptoms:** fatigue, joint pain, brain fog, skin changes, GI issues
- **Strongest lifestyle correlates with better outcomes:** anti-inflammatory diet, regular moderate exercise, stress management, and sleep consistency
- **Demographics most affected by delayed diagnosis:** women aged 20–40, minority populations, patients without specialist access

---

## Tableau Dashboard

> 📊 [View the Interactive Dashboard](#) *(link to Tableau Public)*

Dashboard includes:
- Symptom frequency heatmap by disease type
- Diagnosis delay by demographics
- Lifestyle vs. outcomes scatter plots
- Patient-friendly symptom checklist

---

## Patient Impact

This project goes beyond numbers. The final deliverable includes a **plain-language patient guide** summarizing:
- Common early warning signs to discuss with a doctor
- Questions to ask when seeking a diagnosis
- Evidence-based lifestyle changes that improve quality of life
- Resources and support communities

---

## About the Author

Tayma Nofal is an MBA graduate in Healthcare Administration with experience in hospital operations, international health systems, and strategic planning. This capstone reflects her commitment to bridging the gap between healthcare data and the patients who need it most.

📧 nofal.tayma@gmail.com
🔗 [LinkedIn](#)
