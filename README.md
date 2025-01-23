# Students-Lifestyle-and-Academic-Performance-Analysis
This project investigates how students' lifestyle factors;; study hours, sleep, extracurricular activities, physical activity, and social interactions affect their academic performance. The analysis provides insights and actionable recommendations for optimizing student outcomes.  

## Data Profiling and Cleaning

_Initial Dataset Issues:_

- Inconsistent column headers.
- Presence of unnecessary symbols and formatting errors.

_Actions Taken:_

- Standardized column names for readability.
- Removed irrelevant characters and cleaned data inconsistencies.

## Data Transformation

_New Columns Created:_

- Study Hour Groups: Categorized study hours into ranges using the SWITCH(TRUE) function.
- Extracurricular Activity Hours Groups: Similar grouping applied based on activity duration.
- Sleep Hour Groups: Grouped using predefined hour ranges.
- Physical Activity and Social Hour Groups: Applied similar transformations for consistency.
- Performance Grades: Used IF function to classify GPA as: High Grade (≥3.5); Average Grade (2.5–3.4); Low Grade (<2.5); Visualizations and Reporting

## Visualization

Key visualizations were created to interpret and present data effectively:

- Pie Chart: Stress levels of students.
- Line Graph: Relationship between sleep hours and stress levels.
- Bar Charts: GPA distribution across study hours and physical activity hours.
- Impact of combined lifestyle factors on GPA.
- Scatter Plot: Correlation between study hours and GPA.

## Key Insights

_Stress Levels:_

- 51.4% of students experience moderate stress, while 14.8% face high stress.
- High stress correlates with insufficient sleep (<6 hours).

_Study Hours:_

- Students studying over 9 hours daily achieve higher GPAs.
- GPA improves steadily as study time increases.

_Sleep and GPA:_

- Students sleeping 7–9 hours generally have better academic performance.
- Less than 6 hours or over 12 hours of sleep negatively impacts GPA.

_Physical Activity and GPA:_

- Moderate physical activity (3–6 hours/day) correlates with higher GPAs.
- Excessive physical activity (>9 hours/day) may slightly lower performance.

_Social Hours:_

- Limited social interactions (2–4 hours/day) positively impact GPA.
- Excessive social hours show no significant academic benefits.

_Overall Lifestyle Balance:_

- High-performing students balance study, sleep, and moderate physical activity.
- Students with low grades often have imbalanced lifestyles, characterized by insufficient study and excessive extracurricular activities.

## Recommendations

- Balance Lifestyle: Encourage students to maintain a balanced routine with: 7–9 hours of sleep; 3–6 hours of study; Moderate physical activity (3–6 hours).
- Stress Management: Introduce stress-reduction programs focusing on sleep hygiene and time management.
- Extracurricular Activities: Limit these to 1–3 hours daily to avoid academic decline.
- Personalized Interventions: Tailor strategies for students based on their GPA group.

## Outcome 

- Delivered a comprehensive dashboard illustrating key insights into how lifestyle factors impact academic performance. 
- Provided targeted recommendations to enhance students’ GPA and reduce stress through lifestyle adjustments and institutional support programs. 
