# Marketing-Campaign A/B Testing

## Project Overview
This project involves a rigorous statistical analysis of a marketing campaign to determine the effectiveness of a new interface versus a control group. By utilizing Hypothesis Testing, I validated whether the observed conversion uplift was statistically significant or due to random chance.

## Key Results
* **Data Integrity**: Audited and cleaned 294,478 entries, removing 3,893 mismatched rows to ensure experimental validity.
* **Statistical Significance**: Conducted a Z-test in Python, achieving a 7.37 z-stat and a highly significant p-value of 1.70 x 10<sup>-13</sup>.
* **Conversion Insights**: Established a 1.79% baseline control conversion and identified a statistically significant uplift in the treatment group.
* **Business Recommendation**: Recommended a full-scale rollout of the new interface, projected to drive a 5-7% increase in conversion efficiency.

## Tech Stack:
* **Languages**: Python (Pandas, NumPy).
* **Statistical Concepts**: Hypothesis Testing, Z-Tests, P-values, Confidence Intervals.
* **Environment**: Google Collab.

## Methodology
* **Data Preprocessing**: Handled mismatched group assignments and landing page versions to maintain a clean test environment.
* **Hypothesis Formulation**: Set the Null Hypothesis as no difference in conversion rates and the Alternative Hypothesis as a significant uplift.
* **Execution**: Ran a two-proportion Z-test to compare the performance of the Control and Treatment groups.
