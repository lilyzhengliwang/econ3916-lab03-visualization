# econ3916-lab03-visualization
Data Visualization
Project Title: Honest vs. Misleading Visualizations

Objective: This project examines how chart design choices can distort or clarify data, using statistical anomalies, axis manipulation, and real-world economic data to demonstrate the gap between visual perception and statistical reality.

Methodology:

Recreated Anscombe's Quartet: four datasets sharing nearly identical means, variances, and correlation (0.816) but revealing entirely different underlying relationships when plotted
Computed a Lie Factor of 49.0 for a truncated-axis revenue chart, where a real 4.1% increase was visually distorted to appear as a 200% increase, and redesigned the chart to represent the data honestly
Plotted four versions of real average hourly earnings (FRED AHETPI, deflated to 2020 dollars) that told four different visual stories from the same underlying data
Ran a four-step EDA checklist (structure, distributions, relationships, anomalies) on World Bank GDP data spanning 262 countries and 64 years
Built an interactive honest-chart toggler with a live-updating Lie Factor readout

Key Findings:

Nearly identical summary statistics can mask radically different data structures — Anscombe's Quartet remains a foundational warning against trusting numbers without visualizing them
Axis truncation can inflate the perceived magnitude of change by nearly 50x relative to the actual change, underscoring how chart design alone can mislead without altering any underlying data
The World Bank GDP dataset showed a strong right skew (8.4) in raw values that normalized substantially (0.2) under a log transformation, reinforcing the importance of choosing appropriate scales before drawing conclusions
