# Task 4 – Applications & Shortlisting

## 📌 Project Overview

This project focuses on building an end-to-end Application Funnel for tracking candidate applications from initial submission through screening, shortlisting, verification, interviews, offers and hiring.

The project was completed as part of the Data Analyst – Week 2, Phase 2 study task.

## 🎯 Objective

The main objective is to create a measurable and decision-ready application funnel that helps identify:

- Application volume
- Screening performance
- Shortlisting conversion
- Verified shortlisted candidates
- Interview conversion
- Offer conversion
- Hiring conversion
- Application-source performance
- Funnel bottlenecks

## 🔄 Application Funnel

Applications
↓
Screening Passed
↓
Shortlisted
↓
Verified Shortlist
↓
Interviewed
↓
Offer
↓
Hired

## 📊 Dataset

The dataset contains 1,000 application records.

Important fields include:

- application_id
- candidate_id
- company
- role
- location
- source
- applied_at
- screening_passed
- shortlisted
- verified_shortlist
- interviewed
- offer_received
- hired
- current_stage

## 📈 Key Analysis

The analysis calculates:

- Total applications
- Screening conversion
- Shortlisting conversion
- Verification rate
- Interview conversion
- Offer conversion
- Offer-to-hire conversion
- Overall application-to-hire conversion
- Source-level hiring performance

## 🔍 Key Findings

The overall application-to-hire conversion in the sample dataset is 5.9%.

The funnel analysis highlights the major drop-offs between application stages and provides a way to identify where recruitment processes can be improved.

Source-level performance is also compared to identify channels that generate stronger hiring outcomes.

## 🧹 Data Quality Checks

The project includes checks for:

- Duplicate application IDs
- Missing required values
- Valid timestamps
- Logical funnel progression
- Valid stage flags
- Impossible funnel states

## 💡 Recommendations

1. Monitor funnel conversion rates at every stage.
2. Investigate major drop-offs after screening.
3. Track verified shortlisted candidates separately.
4. Compare hiring performance by application source.
5. Use dashboard filters for role, company and location.
6. Keep every KPI traceable to the underlying application records.

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Google Colab
- CSV
- Data Analysis
- Data Visualization
- GitHub

## 📁 Project Files

- `Task_4_Application_Funnel.csv` – Application funnel dataset
- `Task_4_Applications_Shortlisting_Report.pdf` – Final report
- `Task_4_Applications_Shortlisting.ipynb` – Google Colab analysis notebook
- `README.md` – Project documentation

## ✅ Conclusion

The project demonstrates how application data can be transformed into an end-to-end recruitment funnel. The resulting metrics are traceable, measurable and suitable for dashboard-based decision making.
