# Data-Analysis-Salamonie-1900-2023



This repository encapsulates the Python-based computational framework and analytical procedures employed to examine historical rainfall data for the **Salamonie** station. The study primarily focuses on data preprocessing, trend analysis, and statistical evaluations to discern significant hydrological patterns.

## Data Source
The rainfall dataset spans the period from **1900 to 2023**, provided through the concerted efforts of:
- **Prof. Chandramouli Viswanathan Chandramouli, Ph.D.**, Department Chair of Mechanical and Civil Engineering, and Interim Department Chair of Construction Science and Organizational Leadership at Purdue University.
- The **National Oceanic and Atmospheric Administration (NOAA)**, whose staff facilitated access to daily precipitation records and offered invaluable assistance throughout the data acquisition process.

## Objectives
1. Undertake comprehensive cleaning and preprocessing of the Salamonie rainfall dataset.
2. Address data gaps by employing robust averaging techniques to enhance dataset reliability.
3. Conduct an in-depth temporal analysis of annual rainfall patterns, focusing on identifying and quantifying long-term trends.
4. Utilize advanced statistical methods to evaluate the significance of the detected trends.

## Methodology
### Data Cleaning
- Missing precipitation values were imputed using calculated averages to mitigate inconsistencies in the dataset.
- The dataset was transformed from its original wide format into a long format, optimizing its structure for analytical workflows.

### Statistical Analysis
- **Linear Regression** was employed to quantify directional trends in annual rainfall data.
- The **Mann-Kendall Test**, a non-parametric statistical approach, was applied to determine the statistical significance of these trends.
- A **3-year moving average** was computed to attenuate interannual variability and facilitate the identification of underlying patterns.

### Visualization
- Comprehensive visualizations were constructed using **Matplotlib** and **Seaborn** to elucidate:
  - Monthly rainfall dynamics.
  - Annual rainfall trends, including regression analyses.
  - Long-term smoothing patterns through moving averages.

## Tools and Technologies
- Python libraries utilized include: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scipy`, and `pymannkendall`.
- All preprocessing, analysis, and visualization tasks were executed in Python to ensure reproducibility and scalability.

## Key Insights
The analysis sheds light on enduring hydrological trends at the Salamonie station, contributing to a nuanced understanding of regional rainfall variability. These insights hold implications for both hydrological modeling and environmental resource management.

## Acknowledgments
Gratitude is extended to:
- **Prof. Chandramouli Viswanathan Chandramouli, Ph.D.**, for his scholarly guidance and support throughout the research process.
- The dedicated staff at **NOAA**, whose cooperation and data-sharing initiatives were instrumental in enabling this study.



