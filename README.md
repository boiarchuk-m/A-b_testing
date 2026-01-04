# A/B Test Analysis: Premium Offer Page Conversion Optimization
## Project Overview
This project analyzes an A/B test evaluating the impact of a redesigned premium offer page on conversion rates for Lit Lantern, a mobile e-book and audiobook app.
## Business Context
Lit Lantern uses a freemium model offering users a 7-day premium trial. The goal was to increase the percentage of free users who convert to premium trials by redesigning the offer page with improved messaging and visual hierarchy.
## Test Design
### Hypothesis
- **Null Hypothesis (H₀):** No difference in conversion rates between variants
- **Alternative Hypothesis (H₁):** Variant B achieves ≥5% higher conversion rate
- **Significance Level:** α = 0.05
- **Statistical Power:** 0.80
### Metrics
- **Primary:** Conversion rate (% users starting premium trial)
- **Guardrails:** Session duration, sessions per user

### Repository files
- `A_b_test.ipynb` Jupyter notebook with a test 
- `ab_test_control.csv` control group data
- `ab_test_variant.csv` variant group data
