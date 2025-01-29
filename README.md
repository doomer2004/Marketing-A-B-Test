# A/B Test: New Website Design Impact Analysis

## Overview

This project evaluates the impact of a new website design on key performance metrics using A/B testing. The goal is to determine whether the redesign improves user engagement and revenue-related metrics compared to the existing design.

## Dataset

The dataset contains user interaction data collected during the test period. The key columns include:

- **group**: Indicates whether the user was in the control or test group.
- **country**: The country of the user.
- **impressions**: The number of times the website was shown to users.
- **clicks**: The number of times users clicked on the website.
- **revenue**: The total revenue generated from users.

## Hypothesis

The hypothesis of this A/B test is:

> "The new website design improves key engagement and revenue metrics such as Click-Through Rate (CTR) and Average Revenue Per User (ARPU) without negatively impacting Cost Per Click (CPC)."

## Test Methodology

- Users were randomly split into two groups:
  - **Control Group**: Experienced the original website design.
  - **Test Group**: Experienced the redesigned website.
- The experiment was conducted over a sufficiently long period to collect statistically meaningful data.
- Statistical tests were performed to determine whether the observed differences were significant.

## Key Findings

1. **Overall Test-Level Results**:
   - No statistically significant changes were observed at the total level.
2. **Country-Specific Analysis**:
   - **United Kingdom**: Significant positive impact on CTR and ARPU.
   - **France**: Significant negative impact on CTR and ARPU.
   - **Germany**: No significant changes detected.
   - **Australia**: Significant positive impact on CTR and ARPU.

## Recommendations

- Implement the new design in the United Kingdom and Australia.
- Do not roll out the new design in France due to negative performance.
- Continue testing in Germany to gather more data before making a decision.
