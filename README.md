# Vungle Case Study

This repository contains the detailed analysis of Vungle’s ad-serving algorithms through a data-driven case study. Vungle is a leader in in-app video advertising, and this study explores the performance of two algorithms (A and B) using statistical and machine learning methodologies.

---

## Table of Contents

- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Methodology](#methodology)
  - [Metrics Used](#metrics-used)
  - [Statistical Tests](#statistical-tests)
- [Results and Analysis](#results-and-analysis)
  - [Initial Observations](#initial-observations)
  - [Statistical Testing](#statistical-testing)
  - [Key Findings](#key-findings)
- [Implications](#implications)
- [Recommendations](#recommendations)
- [Conclusions](#conclusions)
- [Authors](#authors)

---

## Introduction

Vungle is a pioneer in mobile advertising, enabling developers to integrate video ads seamlessly into apps. This case study evaluates the effectiveness of a new machine-learning-based ad-serving algorithm designed to maximize ad conversions and increase effective revenue per 1,000 impressions (eRPM).

---

## Problem Statement

Vungle's success depends on its ability to drive app installs through engaging ads. The challenge is to optimize performance metrics like conversion rates and eRPM while balancing user experience and advertiser diversity.

---

## Methodology

### Metrics Used
- **eRPM (Effective Revenue Per Mille):** Tracks revenue per 1,000 impressions.
- **Conversion Rate:** Proportion of impressions resulting in installs.

### Statistical Tests
- **T-Test:** Analyzed mean eRPM differences to determine statistical significance.
- **Paired T-Test:** Compared algorithm performance under identical conditions, accounting for daily variations.
- **Z-Test:** Evaluated conversion rates for larger sample sizes.

---

## Results and Analysis

### Initial Observations
- **Algorithm A Mean eRPM:** $3.347  
- **Algorithm B Mean eRPM:** $3.459  
- **Algorithm A Conversion Rate:** 0.0040%  
- **Algorithm B Conversion Rate:** 0.0035%

### Statistical Testing
- **Paired T-Test:** P-value = 0.002406, indicating a significant performance difference in favor of Algorithm B for eRPM.
- **Z-Test:** P-value ≈ 0, confirming Algorithm A’s superior conversion rate.

### Key Findings
- Algorithm B generated higher short-term revenue but showed a decline in user engagement and conversion rates.
- Algorithm A maintained better conversion performance, critical for long-term platform sustainability.

---

## Implications

1. **User Experience Decline:** Algorithm B risks disengaging users with lower-relevance ads.  
2. **Ad Diversity Imbalance:** Prioritizing high-revenue ads can reduce advertiser inclusivity.  
3. **Long-Term Revenue Decline:** Compromised user trust may lead to fewer impressions over time.  
4. **Brand Reputation Risk:** A degraded user experience can harm Vungle's reputation among users and advertisers.

---

## Recommendations

1. **Optimize Ad Prioritization:** Balance revenue-driven ads with high-conversion opportunities.  
2. **Experiment with Ad Mix:** Test diverse combinations of ads to ensure sustainability.  
3. **Extend A/B Testing:** Expand tests across geographies and demographics.  
4. **Develop Dynamic Models:** Leverage machine learning for real-time ad prioritization.  
5. **Segmented Testing:** Focus on personalized ad delivery strategies.

---

## Conclusions

While Algorithm B maximized short-term revenue, Algorithm A provided better user engagement and conversion rates. The findings underscore the need for balanced strategies to ensure long-term growth and user satisfaction.

---

## Authors

This analysis was conducted as part of academic project at UTDallas.

---

## How to Use This Repository

- The detailed report is available in `Vungle-Report.docx`.
- Statistical analysis and data are organized in the `analysis.xlsx` directories.

---

Thank you for exploring this case study!
