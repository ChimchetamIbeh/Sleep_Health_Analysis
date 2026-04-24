# 😴 Sleep Health & Lifestyle Analysis

A data analysis project exploring the relationships between sleep patterns, lifestyle habits, and health indicators across 374 individuals — built entirely in Microsoft Excel.

---

## 📂 View the File

👉 [Click here to view the full analysis on Google Sheets](https://docs.google.com/spreadsheets/d/1_li2x0qsVHYQSbCh7UTS4PtMdJj0FLpKgu-aqWD_lno/edit?usp=sharing)

## 📸 Dashboard Preview

![Dashboard](screenshots/dashboard.png)

---

## 👩‍💻 Author

**Chimchetam Christabel Ibeh**
Data Analysis Portfolio | Tool: Excel | Year: 2026

---

## 📁 Project Structure

The workbook contains four sheets, each serving a distinct role in the analysis pipeline:

| Sheet | Description |
|---|---|
| `Sleep_Health_and_Lifestyle_data` | Raw dataset with 374 rows and 13 original variables |
| `Working_sheet` | Cleaned and enriched data with engineered features |
| `Pivot_Tables` | Summarised cross-tabulations of key variables |
| `Dashboard` | Visual summary dashboard for storytelling and presentation |

---

## 📊 Dataset Overview

- **Source:** [Kaggle — Sleep Health and Lifestyle Dataset](https://www.kaggle.com/)
- **Records:** 374 respondents
- **Age Range:** 27 – 59 years
- **Gender Split:** 189 Male | 185 Female

### Variables in Raw Data

| Variable | Description |
|---|---|
| Person ID | Unique identifier |
| Gender | Male / Female |
| Age | Age in years |
| Occupation | Job role (11 categories) |
| Sleep Duration | Average hours of sleep per night |
| Quality of Sleep | Self-rated sleep quality (1–10) |
| Physical Activity Level | Minutes of daily activity |
| Stress Level | Self-rated stress (1–10) |
| BMI Category | Normal Weight / Overweight / Obese |
| Blood Pressure | Systolic/Diastolic reading |
| Heart Rate | Resting heart rate (bpm) |
| Daily Steps | Average steps per day |
| Sleep Disorder | None / Sleep Apnea / Insomnia |

---

## 🛠️ Feature Engineering (Working Sheet)

The following new columns were derived from the raw data to enable richer analysis:

- **Age (Grouped)** — Age brackets (e.g., 20–29yrs, 30–39yrs)
- **Sleep Duration (Grouped)** — Binned into hourly ranges (e.g., 6.0–6.9 hrs)
- **Physical Activity Level (Grouped)** — Grouped into activity bands (e.g., 30–39, 60–69)
- **Blood Pressure (Systolic)** — Extracted from combined BP string
- **Blood Pressure (Diastolic)** — Extracted from combined BP string

---

## 🔍 Key Findings

| Metric | Value |
|---|---|
| Average Sleep Duration | 7.13 hours |
| Average Quality of Sleep | 7.31 / 10 |
| Average Stress Level | 5.39 / 10 |
| Respondents with No Sleep Disorder | 219 (58.6%) |
| Respondents with Sleep Apnea | 78 (20.9%) |
| Respondents with Insomnia | 77 (20.6%) |

**BMI Distribution:**
- Normal Weight: 216 (57.8%)
- Overweight: 148 (39.6%)
- Obese: 10 (2.7%)

**Occupations covered:** Software Engineer, Doctor, Nurse, Teacher, Engineer, Accountant, Scientist, Lawyer, Sales Representative, Salesperson, Manager

---

## 📈 Analysis Highlights

- Compared **Sleep Disorder vs Sleep Quality** across demographic groups
- Explored how **occupation and stress levels** relate to sleep patterns
- Investigated the link between **BMI category and sleep disorders**
- Segmented respondents by **age group and activity level** for trend analysis

---

## 🚀 How to Use

1. Download the `.xlsx` file from this repository
2. Open in **Microsoft Excel** (recommended) or Google Sheets
3. Navigate between sheets using the tabs at the bottom:
   - Start with `Sleep_Health_and_Lifestyle_data` for the raw data
   - Go to `Working_sheet` for the enriched dataset
   - Explore `Pivot_Tables` for summaries
   - View the `Dashboard` for the visual overview

---

## 📌 Tools Used

- **Microsoft Excel** — Data cleaning, feature engineering, pivot tables, dashboard
