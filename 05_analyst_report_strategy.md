# 📊 STRATEGY 5 — ANALYST REPORT WRITING GUIDE
## Arun Pandian | Write Reports That Get You Hired

> Your portfolio already has 3 case studies. This guide turns each one
> into a professional analyst report that reads like it came from
> McKinsey, Deloitte, or a Product Analytics team.

---

## 🏆 THE 5 TYPES OF ANALYST REPORTS

| Type | When to Use | Your Best Example to Do First |
|------|------------|-------------------------------|
| **Exploratory Report** | First look at new dataset | Uber project → Ride pattern EDA |
| **Business Case Study** | Problem → Solution → Impact | Job Market Dashboard |
| **Funnel Analysis Report** | User journey / conversion | funnel-analysis repo |
| **Predictive Report** | Forecast + model | disease-prediction-ml → Churn report |
| **Industry Benchmark Report** | Compare companies/sectors | Job Market Salary Benchmarking |

---

## 📐 THE PROFESSIONAL REPORT STRUCTURE

### 🔹 Section 1: Cover Page
```
┌─────────────────────────────────────────┐
│                                         │
│  [COMPANY / DOMAIN] ANALYTICS REPORT   │
│                                         │
│  Topic: [Specific Insight Title]        │
│  Author: Arun Pandian, Data Analyst     │
│  Date: [Month Year]                     │
│  Tools: SQL · Python · Power BI · Excel │
│                                         │
│  arunpandian.online | GitHub link       │
└─────────────────────────────────────────┘
```

### 🔹 Section 2: Executive Summary (THE MOST IMPORTANT SECTION)
**Rule:** Any executive should understand your entire report in 60 seconds from this section alone.

**Template:**
```
EXECUTIVE SUMMARY

This report analyzes [X dataset / domain] to address [specific business question].

Key findings:
• [Most important insight — lead with the number]
• [Second insight]
• [Third insight]

Recommendation: [One clear, actionable recommendation]
Expected impact: [Metric improvement / cost saving / revenue opportunity]
```

**Real Example (from your Job Market project):**
```
EXECUTIVE SUMMARY

Analysis of 2023 data science job postings (n=18,000+) reveals that:
• SQL remains the #1 required skill, appearing in 62% of all postings
• Python commands the highest median salary ($105,000) among top 10 skills
• US-based roles pay 3.2× more than India-based roles for the same title
• Candidates with 3+ skills earn 28% more than single-skill specialists

Recommendation: Data professionals should prioritize SQL + Python before specializing,
as this combination maximizes both employability and earning potential.
```

---

### 🔹 Section 3: Problem Statement
Answer these 4 questions:
1. **Business context:** What industry / company type is this relevant to?
2. **Decision question:** What decision does this data help make?
3. **Stakeholder:** Who benefits from this analysis? (CMO, Operations, Finance)
4. **Scope:** What's included / excluded?

---

### 🔹 Section 4: Data Profile
| Field | Value |
|-------|-------|
| Dataset name | |
| Source | Kaggle / API / Web scrape / Internal |
| Volume | X rows × Y columns |
| Time period | |
| Key fields | |
| Data quality issues | Nulls: X% / Duplicates: X / Outliers: |
| Cleaning actions | |

---

### 🔹 Section 5: Analysis (The Core)

**Use the INSIGHT-EVIDENCE-SO WHAT Framework for each finding:**

```
FINDING 1: [Bold, specific headline like "SQL demand spiked 40% in Q4 2023"]

INSIGHT: SQL appeared in 62% of data analyst job postings in 2023,
         making it the most requested technical skill by a wide margin.

EVIDENCE: [Chart / Table / Query result]
  - Top 5 skills by posting frequency:
    1. SQL     — 62% of postings
    2. Python  — 58% of postings
    3. Excel   — 49% of postings
    4. Power BI— 34% of postings
    5. Tableau — 29% of postings

SO WHAT: Companies hiring data analysts overwhelmingly expect SQL proficiency.
         Analysts without SQL are screened out before the interview stage
         in nearly 6 out of 10 roles.
```

---

### 🔹 Section 6: Visualizations

**For every report, include these charts:**

| Chart Type | When to Use | Tool |
|-----------|------------|------|
| **Bar chart** | Comparing categories | Power BI / Plotly / Excel |
| **Line chart** | Trends over time | Plotly / Power BI |
| **Scatter plot** | Correlation / outliers | Python (Seaborn) |
| **Heatmap** | Correlation matrix | Python (Seaborn) |
| **Funnel chart** | Conversion / drop-off | Power BI / Plotly |
| **Map** | Geographic data | Folium / Power BI |
| **Box plot** | Distribution / salary | Python |

**Chart Design Rules:**
- Every chart needs a title that IS the insight (not just "Sales by Month")
  - ❌ "Sales by Month"
  - ✅ "Sales Peaked in December — 2.4× Above January Average"
- Label the axes
- Add a data source note
- Use consistent colors

---

### 🔹 Section 7: Recommendations

Use the **Impact / Effort Matrix** format:

| Priority | Recommendation | Impact | Effort | Timeline |
|---------|---------------|--------|--------|---------|
| 🔴 HIGH | [Most important action] | High | Low | Week 1 |
| 🟡 MEDIUM | [Second action] | Medium | Medium | Month 1 |
| 🟢 LOW | [Third action] | Low | High | Quarter |

---

### 🔹 Section 8: Appendix (Code + Data)

```python
# Always include your SQL / Python code
# Cleaned and commented

SELECT
    skill_name,
    COUNT(*) AS posting_count,
    ROUND(COUNT(*) * 100.0 / (SELECT COUNT(*) FROM job_postings), 1) AS pct
FROM job_skills
GROUP BY skill_name
ORDER BY posting_count DESC
LIMIT 10;
```

---

## 📂 YOUR 5 NEXT REPORTS TO WRITE

Based on your existing repos, here are 5 reports you can write THIS WEEK:

### Report 1: Upgrade Your Job Market Analysis
**Current:** Excel dashboard
**Upgrade:** Add a proper 6-section analyst report
**New title:** "2023 Data Science Job Market: Which Skills Pay, Which Don't, and Why"

### Report 2: Funnel Analysis Deep Dive
**Repo:** `funnel-analysis` (Jupyter Notebook)
**Report:** "User Acquisition Funnel Analysis: Where Customers Drop Off and How to Fix It"

### Report 3: Uber/Ride Data Report
**Repo:** `uber-project`
**Report:** "Ride Demand Patterns: Peak Hours, Surge Pricing Opportunities, and Driver Supply Gaps"

### Report 4: Disease Prediction Model Card
**Repo:** `disease-prediction-ml` / `chronical-disease-prediction`
**Report:** "Chronic Disease Early Warning System: Model Performance, Bias Analysis, and Clinical Recommendations"

### Report 5: XAI Dashboard Report
**Repo:** `XAI-Seizure-predicion-dashboard`
**Report:** "Explainable AI for Seizure Prediction: Interpretability vs. Accuracy Trade-offs"

---

## 🚀 DISTRIBUTION STRATEGY — Where to Publish Reports

| Platform | Format | Audience |
|---------|--------|---------|
| **GitHub** | README.md + PDF | Developers + recruiters |
| **arunpandian.online blog** | Blog post | General + recruiters |
| **LinkedIn Article** | Long-form post | Professionals |
| **Kaggle Notebooks** | Interactive notebook | Data science community |
| **Medium / Towards Data Science** | Article | 500K+ data science readers |

### Medium / TDS Submission Template:
```
Title: "I analyzed [X] data for [Y] hours. Here's what I found."
Hook (first line): Start with the most surprising number.
Body: Summarize 3 key findings in plain English.
CTA: "Full report on GitHub / my portfolio → [link]"
```

---

## 📏 QUALITY CHECKLIST — Before Publishing Any Report

- [ ] Executive summary is standalone (makes sense without reading the rest)
- [ ] Every finding has evidence (chart, table, or query)
- [ ] Every chart has a title that IS the insight
- [ ] Recommendations are specific and actionable (not "improve the process")
- [ ] Code is available on GitHub and linked
- [ ] Spelling and grammar checked (Grammarly)
- [ ] PDF version available for download
- [ ] LinkedIn post drafted and scheduled
- [ ] GitHub README updated with the report link
