# Statistical Analysis of Caffeine Intake Among Students of Faculty of Science

*The ABC Insights: Analyzing Brewed Chai Coffee Caffeine*

B.Sc. (Hons.) Statistics project | Department of Statistics, Faculty of Science, The Maharaja Sayajirao University of Baroda | 2025

---

## Overview

This project studies caffeine consumption among Faculty of Science students. It examines how caffeine intake relates to sleep, focus, academic performance (CGPA), gender, and year of study, and how consumption changes between regular days and exam days. Questionnaire-based primary data is combined with campus market data and laboratory caffeine quantification.

## Objectives

- Examine consumption patterns and trends, including frequency, amount, and brand
- Analyse the relationship between caffeine intake and sleep quality
- Investigate reasons for starting caffeine consumption and related health effects
- Study the relationship between caffeine intake, academic performance, and focus intervals
- Compare average caffeine intake by gender, year of study, and department

## Methodology

**1. Market data collection**
Recorded tea and coffee brands and cup sizes from shops and stalls on campus and within a 1 km radius. The most common cup size was 100 ml.

**2. Questionnaire design and validation**
- Pilot survey on 30 randomly selected students; questions were reworded based on feedback
- Reliability checked with Cronbach's alpha (α ≈ 0.74 for the scored sections)

**3. Sampling**
- Population: 3,829 students
- Sample size: 298 (95% confidence, 5% margin of error, p = 0.7, finite population correction)
- Stratified random sampling with proportional allocation by year of study

| Year of study | Students | Sample |
| --- | --- | --- |
| F.Y. | 1069 | 80 |
| S.Y. | 720 | 62 |
| T.Y. | 943 | 76 |
| M.Sc. (Previous) | 593 | 41 |
| M.Sc. (Final) | 504 | 39 |

**4. Laboratory analysis**
Caffeine in tea and coffee samples was quantified by iodometric back titration, using iodine and standardised sodium thiosulfate with starch as the indicator.

**5. Statistical analysis**
Intake data was right-skewed and failed normality (Shapiro-Wilk, p < 0.05), so non-parametric methods were used:

- Wilcoxon rank-sum test: regular vs. exam days, and gender comparisons
- Kruskal-Wallis test: differences across sleep, focus, and CGPA groups
- Jonckheere-Terpstra test: ordered trends across groups
- Histograms, boxplots, and bar charts for visualisation

## Key Findings

- **Exam effect:** Median caffeine intake is significantly higher on exam days than on regular days (p = 0.044).
- **Sleep:** Higher caffeine intake is associated with a decreasing trend in sleep hours, on both regular days (p = 0.018) and exam days (p = 0.008).
- **Focus:** Caffeine intake differs significantly across focus-interval groups on regular days (p = 0.008) and exam days (p = 0.005), with a significant increasing trend during exams (p = 0.037).
- **CGPA:** No significant relationship on regular days. During exams, higher intake is associated with higher CGPA (p = 0.001). This is an association, not evidence of causation.
- **Gender:** Intake differs significantly between genders on regular days (p = 0.014), but not clearly during exams (p = 0.053).
- **Brands:** Nescafé (78% of coffee responses) and Wagh Bakri (60% of tea responses) were the most preferred.
- **Awareness:** A notable share of students exceeded the 200 mg benchmark, especially on exam days, supporting a "Sip Smart: Stay Below 200" awareness initiative.

## Tools

R, Microsoft Excel, laboratory titration

## Limitations

- Caffeine values are estimates and vary with preparation method, ingredients, and serving size.
- Intake is self-reported and may be affected by recall bias or reluctance to report symptoms.
- The study covers one faculty at one university, so results may not generalise to other populations.

## Team

Jamil Mahida, Nikita Sharma, Rajvee Shah, Savantsinh Rathod, Tanya Chaurasia

**Guides:** Dr. (Mrs.) M. N. Shah, Mr. Vijay K. Gupta
**Head of Department:** Prof. V. A. Kalamkar

## Acknowledgements

Thanks to the Department of Statistics and the Department of Chemistry, MSU Baroda, for their guidance and laboratory support, and to all the students who took part in the survey.
