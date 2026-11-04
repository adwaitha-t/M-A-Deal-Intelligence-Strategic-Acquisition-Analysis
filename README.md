# M&A Deal Intelligence & Strategic Acquisition Analysis

### Global M&A Trends, Financial Benchmarking & India Healthcare Market Analysis (2019–2026)

## Project Overview

This project focuses on analyzing mergers and acquisitions (M&A) activity across global markets, with a deeper examination of the healthcare and life sciences sector and India-related transactions.

The objective is to understand M&A trends, evaluate transaction patterns, benchmark disclosed deal values, identify prominent market participants, and develop a preliminary strategic acquisition target-screening framework.

Using Python for data cleaning and exploratory analysis and Microsoft Excel for financial analysis and interactive visualization, this project transforms raw transaction data into structured business insights that can support strategic planning and investment research.

## Business Objectives

- Analyze historical global M&A activity across healthcare and life sciences.
- Identify annual transaction trends and changes in deal activity.
- Examine domestic and cross-border M&A transactions involving India.
- Identify leading acquirers and frequently appearing acquisition targets.
- Evaluate disclosed transaction values and compare financial benchmarks.
- Develop a preliminary framework for screening strategically relevant acquisition targets.
- Build an interactive Excel dashboard to communicate key findings.

## Dataset Overview

**Dataset:** Mergers & Acquisitions 2019–2026 Sample

| Attribute | Details |
|---|---|
| Total records | 30,887 |
| Time period | 2019–2026 |
| Geographic coverage | Global |
| Primary focus | Healthcare and Life Sciences |
| Financial data | Disclosed deal values in USD |

**Key dataset attributes:**
- Deal ID and announcement date
- Acquirer and target company names
- Acquirer and target countries
- Industry sector
- Transaction type and deal status
- Stake percentage
- Disclosed deal value
- Cross-border transaction indicator

## Tools & Technologies

| Technology | Application |
|---|---|
| Python | Data cleaning and exploratory analysis |
| Pandas | Data manipulation and transformation |
| NumPy | Numerical analysis |
| Matplotlib | Data visualization |
| Jupyter Notebook | Analysis and documentation |
| Microsoft Excel | Financial analysis and dashboard development |
| PivotTables | Transaction summarization |
| Excel Slicers | Interactive dashboard filtering |

## Project Methodology

### 1. Data Cleaning & Preparation

- Loaded and explored 30,887 M&A transaction records.
- Standardized date and text fields.
- Checked duplicate transaction IDs and missing values.
- Evaluated data completeness across financial and transaction attributes.
- Developed a preliminary keyword-based classification to identify healthcare and life sciences transactions.

### 2. Global Healthcare & Life Sciences M&A Analysis

- Identified 2,218 transactions under the preliminary core healthcare and life sciences classification.
- Analyzed annual M&A activity from 2019 to 2026.
- Examined transaction activity across healthcare, life sciences, diagnostics, biotechnology and related sectors.
- Identified changes in transaction activity over the analysis period.

### 3. India-Related M&A Analysis

- Identified 224 healthcare transactions involving Indian acquirers or targets.
- Classified transactions into:
  - Domestic transactions
  - Foreign acquirers acquiring Indian targets
  - Indian acquirers acquiring foreign targets
- Analyzed major acquirers and frequently appearing acquisition targets.
- Examined domestic and cross-border transaction patterns.

### 4. Financial Benchmarking

- Identified 75 transactions with deal values marked as verified in the dataset.
- Calculated total, average and median disclosed deal values.
- Compared financial metrics across domestic and cross-border transaction categories.
- Evaluated the impact of large transactions on average deal values.

### 5. Strategic Acquisition Target Screening

Developed a preliminary target-screening framework to identify companies with potential strategic relevance to healthcare, diagnostics, genomics, biotechnology and life sciences.

Targets were classified into four categories:

- **High:** Preliminary strategic relevance.
- **Medium:** Potential relevance requiring further evaluation.
- **Review:** Additional company identity or business verification required.
- **Exclude:** Limited strategic alignment based on available information.

This screening provides an initial framework for identifying potential acquisition opportunities and is not a definitive investment recommendation.

## Key Findings & Business Insights

### 1. Healthcare M&A Activity

- Identified 2,218 transactions under the preliminary core healthcare and life sciences classification.
- Recorded 355 transactions in 2025, the highest annual count in the dataset.
- Observed an increase in transaction activity in 2021, followed by a correction in 2022 and renewed growth in 2025.

### 2. India-Related M&A Activity

Out of 224 India-related healthcare transactions:

| Transaction Category | Deals | Share |
|---|---:|---:|
| Domestic | 109 | 48.66% |
| Foreign Acquirer – Indian Target | 60 | 26.79% |
| Indian Acquirer – Foreign Target | 55 | 24.55% |
| **Total** | **224** | **100%** |

Domestic transactions represented the largest share of the identified transaction count.

### 3. Financial Insights

Financial analysis was conducted using 75 transactions marked as verified-value deals in the dataset.

| Financial Metric | Result |
|---|---:|
| Number of deals | 75 |
| Total disclosed deal value | $22.63 Billion |
| Average deal value | $301.76 Million |
| Median deal value | $47.16 Million |

**Key observation:** Foreign acquirers acquiring Indian targets accounted for approximately 59.65% of the total disclosed value among the 75 selected transactions.

The substantial difference between average and median deal values indicates that a relatively small number of large transactions influence the overall average.

### 4. Strategic Target Screening

- Identified 21 potentially relevant Indian-target transactions through sector-based screening.
- Classified potential targets according to preliminary strategic relevance.
- Highlighted diagnostics, genomics and life sciences as areas for further investigation.

## Interactive Excel Dashboard

An interactive Microsoft Excel dashboard was developed to present the analysis through KPI cards, PivotTables, charts and slicers.

**Key Performance Indicators:**
- Total India-related healthcare deals
- Dataset-marked verified-value deals
- Total disclosed deal value
- Median deal value

**Dashboard Visualizations:**
- Annual healthcare M&A deal activity
- Domestic and cross-border transaction distribution
- Disclosed deal value by transaction type
- Preliminary acquisition target-screening distribution

**Interactive Filters:**
- Healthcare transaction year
- Deal status
- Financial analysis year
- Target relevance category

## Business Applications

The analytical framework demonstrates capabilities relevant to:

- **M&A Research:** Monitoring transaction activity and identifying market participants.
- **Financial Analysis:** Evaluating disclosed deal values and transaction benchmarks.
- **Market Intelligence:** Understanding industry trends and geographic transaction patterns.
- **Strategic Planning:** Identifying potential acquisition areas and evaluating target relevance.
- **Business Reporting:** Converting complex transaction data into interactive dashboards and actionable insights.

## Limitations & Assumptions

- Industry classification is preliminary and based on keyword matching; it is not an independently validated industry taxonomy.
- The dataset contains missing deal values. Undisclosed values have not been treated as zero.
- The 75 financial transactions are marked as verified by the dataset; this does not establish independent verification of the underlying deal information.
- Company identities, business activities and transaction details require independent validation before investment decisions.
- Target screening is exploratory and does not represent a formal valuation or investment recommendation.
- 2026 represents a partial year and should not be directly compared with complete calendar years.

## Repository Structure

```text
M&A-Deal-Intelligence/
│
├── data/
│   └── mergers_acquisitions_2019_2026_sample.csv
│
├── notebooks/
│   └── MA_Deal_Intelligence_Analysis.ipynb
│
├── dashboard/
│   └── MA_Deal_Intelligence_Dashboard.xlsx
│
├── images/
│   └── dashboard_screenshot.png
│
└── README.md
```

*Update filenames and folder structure to match the files actually uploaded to your repository.*

## Conclusion

This project combines M&A transaction analysis, financial benchmarking, market intelligence and preliminary acquisition target screening to explore global healthcare and life sciences transactions, with a specific focus on India.

By integrating Python-based exploratory analysis with an interactive Microsoft Excel dashboard, the project demonstrates the ability to transform raw transaction data into structured business insights that can support strategic research, investment analysis and corporate decision-making.

---

### Skills Demonstrated

M&A Analysis | Financial Benchmarking | Strategic Target Screening | Market Research | Business Intelligence | Python | Pandas | NumPy | Matplotlib | Microsoft Excel | Data Visualization
