# 🌿 Bellabeat App User Behavior Analysis

![Google Data Analytics](https://img.shields.io/badge/Google-Data%20Analytics%20Capstone-4285F4?style=flat-square&logo=google)
![Tool](https://img.shields.io/badge/Tools-Python%20%7C%20Google%20Sheets-brightgreen?style=flat-square)
![Presentation](https://img.shields.io/badge/Presentation-PowerPoint-B7472A?style=flat-square&logo=microsoftpowerpoint)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=flat-square)
![Domain](https://img.shields.io/badge/Domain-Health%20%26%20Wellness-teal?style=flat-square)

> **Data-Driven Insights to Enhance User Engagement and Wellness**
> *Capstone project completed as part of the Google Data Analytics Professional Certificate — July 2026*

---

## 📌 Project Overview

This case study was completed as the capstone project of the **Google Data Analytics Professional Certificate**. Acting as a junior data analyst for **Bellabeat** — a high-tech wellness company for women — the goal was to analyse smart device usage data and generate actionable marketing recommendations for the Bellabeat App.

The analysis follows the full data analysis lifecycle: **Ask → Prepare → Process → Analyze → Share → Act**

---

## 🎯 Business Task

> *"Analyse smart device usage data to understand how consumers use non-Bellabeat smart devices, and use those insights to guide Bellabeat's marketing strategy."*

**Three guiding questions:**
1. What are the trends in smart device usage?
2. How could these trends apply to Bellabeat customers?
3. How could these trends help influence Bellabeat's marketing strategy?

**Stakeholders:** Urška Sršen (Co-founder & CCO), Sando Mur (Co-founder), Bellabeat Marketing Analytics Team

---

## 🗂️ Dataset

| Detail | Info |
|---|---|
| **Source** | [FitBit Fitness Tracker Data — Kaggle (Möbius)](https://www.kaggle.com/datasets/arashnic/fitbit) |
| **License** | CC0 Public Domain |
| **Files Used** | `dailyActivity_merged.csv`, `sleepDay_merged.csv` |
| **Coverage** | ~30 Fitbit users, approximately one month of data |
| **Records** | 940 daily activity records · 410 sleep records |

### ⚠️ Data Limitations
- Data is from **Fitbit users**, not confirmed Bellabeat customers
- **Small sample size** — not representative of Bellabeat's full user base
- **Short time window** — ~one month; may not capture seasonal patterns
- **No demographic context** — age, gender, stress, and hydration data are absent

> Results should be read as **behavioral trends**, not definitive conclusions about Bellabeat's customer base.

---

## 🛠️ Tools & Process

| Phase | Tool Used | Action |
|---|---|---|
| Prepare | Google Sheets | Downloaded, organised, and stored raw CSV files |
| Process | Google Sheets | Cleaned data — removed duplicates, standardised date formats, selected key variables |
| Analyse | Python (Pandas, Matplotlib, Seaborn) | Descriptive statistics, correlation analysis, visualisations |
| Share | Microsoft PowerPoint | 11-slide executive presentation with data-driven storytelling |

### Data Cleaning Steps
- Verified no null or missing values in the activity dataset
- Identified and removed **3 duplicate rows** from the sleep dataset
- Standardised date formats across both files
- Selected key variables: `TotalSteps`, `Calories`, `SedentaryMinutes`, `VeryActiveMinutes`, `TotalMinutesAsleep`, `TotalTimeInBed`

---

## 🔍 Key Insights

### Insight 01 — Most Users Don't Reach 10,000 Steps
| Metric | Value |
|---|---|
| Average daily steps | **7,616** |
| Users reaching ≥ 10,000 steps | **32.23%** |
| Users falling below goal | **67.77%** |

> **Opportunity:** Personalised step goals, timely reminders, and activity challenges could help close this gap.

---

### Insight 02 — Sedentary Behaviour Dominates the Day
- Sedentary time averages **~16.5 hours/day**
- Active time (light + fair + very active) totals only **~3.8 hours/day**

> **Opportunity:** Inactivity alerts and movement reminders could help break up long sedentary stretches.

---

### Insight 03 — Nearly Half of Users Achieve Healthy Sleep
| Metric | Value |
|---|---|
| Average sleep duration | **6.99 hours** |
| Sessions in healthy range (7–9 hrs) | **46%** |
| Sessions below recommended amount | **44%** |
| Sessions exceeding range | **10%** |

> **Opportunity:** Sleep tracking and bedtime reminders could help users consistently reach a healthy range.

---

### Insight 04 — Steps and Calories Show a Moderate Positive Relationship
| Metric | Value |
|---|---|
| Correlation coefficient | **r = 0.59** |
| Variation in calories explained by steps | **R² = 0.35** |

> **Opportunity:** Reinforces the core value proposition of activity tracking in the Bellabeat App.

---

### Insight 05 — Users Need Proactive, Personalised Support
Together, the data paints a clear picture:
- **68%** of records fall short of the 10,000-step goal
- **~16.5 hrs** spent sedentary on an average day
- **44%** of sleep sessions run under 7 hours

> Users need more than passive tracking — they need **proactive, personalised guidance.**

---

## 💡 Recommendations

| # | Recommendation | Rationale |
|---|---|---|
| 1 | **Personalised Step Goals & Achievement Badges** | Tailor targets to individual baselines; celebrate milestones to drive motivation |
| 2 | **Inactivity Alerts & Movement Reminders** | Prompt users to stand and move during long sedentary stretches |
| 3 | **Sleep Tracking & Bedtime Reminders** | Help users build consistent routines that support 7–9 hours of sleep |
| 4 | **Personalised Wellness Insights & Progress Tracking** | Turn raw data into clear, motivating narratives about individual progress |

> **Core positioning:** Market the Bellabeat App as a **proactive wellness assistant**, not just a passive data tracker.

---

## 📊 Deliverables

| File | Description |
|---|---|
| `Bellabeat_App_User_Behavior_Analysis.pptx` | 11-slide executive presentation with all insights and recommendations |
| `Bellabeat_Case_Study.docx` | Full data journal documenting the Ask → Act process |

---

## 📁 Project Structure

```
Bellabeat-Case-Study/
│
├── Bellabeat_App_User_Behavior_Analysis.pptx   # Final presentation
├── Bellabeat_Case_Study.docx                   # Data journal & process documentation
└── README.md                                   # Project overview (this file)
```

---

## 🚀 How to View This Project

1. Download `Bellabeat_App_User_Behavior_Analysis.pptx` to view the full presentation
2. Download `Bellabeat_Case_Study.docx` to review the analysis journal and methodology
3. Dataset is publicly available on [Kaggle](https://www.kaggle.com/datasets/arashnic/fitbit)

---

## 👤 Author

**Sagar Velip**
📧 sagarvelip.data.analyst@gmail.com
🔗 [LinkedIn Profile] : https://www.linkedin.com/in/sagar-velip-7a289538b/

---

*Completed as the Google Data Analytics Professional Certificate Capstone — July 2026*
*Dataset: FitBit Fitness Tracker Data (CC0 Public Domain) via Kaggle*
