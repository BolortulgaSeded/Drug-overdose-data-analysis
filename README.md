**Accidental Drug-Related Deaths in Connecticut (2012–2024)**
An exploratory data analysis and statistical investigation of accidental drug-related deaths in Connecticut, examining trends in substance involvement, demographic patterns, and polydrug use over a 12-year period.

**Overview**
Drug overdose deaths in Connecticut rose from 355 in 2012 to a peak of 1,524 in 2021 — a 329% increase. This project analyses 12,963 death records across 49 features to uncover which substances are driving the crisis, who is most affected, and how patterns have shifted over time.

**Key Findings**
- **Fentanyl dominates** — detected in 68% of all cases, overtaking heroin as the primary substance around 2016
- **Cocaine involvement is high** — present in 39.8% of cases, often alongside opioids
- **Polydrug use is common** — the majority of cases involve two or more substances detected simultaneously
- **No significant age difference by sex** — independent samples t-test (t = −1.06, p = 0.29) found no statistically significant difference in mean age between male (44.3) and female (44.6) victims
- **Males account** for 73.9% of all deaths.

- **What I Did**
- Data Cleaning — Parsed dates, extracted year features, assessed missing values across 49 columns (12,963 records)
- Exploratory Data Analysis — Produced 7 figures covering yearly death trends, age distributions, substance detection rates, racial demographics, and polydrug patterns
- Substance Trend Analysis — Tracked year-over-year detection rates for fentanyl, heroin, cocaine, benzodiazepine, and ethanol, identifying the 2016 fentanyl crossover point
- Polydrug Analysis — Counted co-occurring substances per case to quantify the scale of polydrug involvement
- Hypothesis Testing — Conducted an independent samples t-test comparing age distributions between male and female victims (α = 0.05)
- KDE Visualisation — Overlaid kernel density estimates on age histograms to visualise distributional similarity between sexes.

- **Visualisations**
- Fig 1EDA overview — deaths per year, age by sex, sex distribution, top locations
- Fig 2Key substance detection trends per year (2012–2024)
- Fig 3Total detections per substance
- Fig 4Age distribution boxplot by sex
- Fig 5Deaths by race
- Fig 6Number of substances detected per case (polydrug)
- Fig 7Age distribution with KDE and t-test result

Tech Stack
- Python
- pandas, NumPy
- Matplotlib
- SciPy (t-test, Gaussian KDE)

Author 
Bolortulga Seded MSc Big Data and Data Science, Northumbria University LOndon
