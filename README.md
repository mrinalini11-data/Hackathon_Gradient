# VoltRelay Energy | EV Battery Swapping Network Analytics

## Project Overview

**Can an EV battery-swapping network scale its operations without compromising service reliability and profitability?**

This project analyses approximately **3.9 million simulated battery-swapping events** across six Indian cities to evaluate the operational performance, battery health, customer experience, and unit economics of VoltRelay Energy.

The objective was to move beyond descriptive reporting and identify operational inefficiencies, investigate their possible causes, and translate data into actionable business recommendations.

## Business Problems

The analysis focuses on five key business questions:

- Which stations contribute disproportionately to service failures?
- How do vehicle categories and city locations affect swap reliability?
- Are battery suppliers delivering consistent battery quality?
- What is the relationship between battery health and operational performance?
- Is network growth translating into improved contribution margins?

## Key Findings

| Business Area | Key Finding |
|---|---|
| Service Reliability | Failure rates increased from **3.98% to 7.86%** between the first and last three months. |
| Station Performance | The worst-performing 10% of stations accounted for **22.6% of service failures**, despite handling only 15.2% of attempts. |
| Vehicle Category | Three-wheelers recorded a **9.95% failure rate**, compared with 5.02% for two-wheelers. |
| Battery Quality | Kyron batteries showed approximately **9.48 SOH percentage points of degradation per 100 cycles**, compared with around 3.02–3.03 for other suppliers. |
| Unit Economics | CM2 per completed swap increased by **93.2%** across the first-three-month and last-three-month comparison periods. |

## Business Recommendations

1. Prioritise high-demand stations with consistently poor service reliability before expanding the network.
2. Introduce supplier-level battery quality monitoring and investigate faster battery degradation.
3. Improve inventory planning to reduce battery stockouts.
4. Evaluate pricing changes through controlled analysis before implementing network-wide changes.
5. Assess fleet partnerships using contribution margin rather than revenue alone.

## Technical Approach

- Data cleaning, preprocessing and validation
- Exploratory Data Analysis (EDA)
- Relational data integration across eight datasets
- Station and city performance analysis
- Battery degradation and supplier comparison
- Contribution margin analysis (CM1, CM2 and CM3)
- Statistical testing and time-series analysis
- Business recommendations based on analytical findings

## Technology Stack

**Python | Pandas | NumPy | SciPy | Statsmodels | Matplotlib | Seaborn | Jupyter Notebook**

## Project Outcome

The project demonstrates how large-scale operational data can be converted into business intelligence. Instead of treating growth as the only success metric, the analysis highlights the importance of service reliability, battery quality, operational efficiency and sustainable unit economics.

**Core takeaway:** Scaling a network is not enough. A business must understand where performance is breaking down and where investment can create the greatest operational improvement.

*Note: The dataset is synthetic and represents a simulated battery-swapping network. Findings describe the dataset and should not be interpreted as actual VoltRelay business results.*
