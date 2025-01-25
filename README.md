
# Students' Lifestyle and Academic Performance Analysis

This project investigates the influence of students' lifestyle factors—study hours, sleep, extracurricular activities, physical activity, and social interactions—on their academic performance. The analysis provides actionable insights and recommendations for optimizing student outcomes.

---

## Data Profiling and Cleaning

### Initial Dataset Issues:
- Inconsistent column headers.
- Presence of unnecessary symbols and formatting errors.

### Actions Taken:
- Standardized column names for readability.
- Removed irrelevant characters and cleaned data inconsistencies.

---

## Data Transformation

### New Columns Created:
- **Study Hour Groups**: Categorized study hours into ranges using the `SWITCH(TRUE)` function.
- **Extracurricular Activity Hours Groups**: Grouped based on activity duration.
- **Sleep Hour Groups**: Grouped using predefined hour ranges.
- **Physical Activity and Social Hour Groups**: Applied consistent transformations.
- **Performance Grades**: Classified GPA as follows:
  - High Grade: GPA ≥ 3.5
  - Average Grade: GPA 2.5–3.4
  - Low Grade: GPA < 2.5

---

## Visualization

Key visualizations were created to effectively interpret and present the data:

- **Pie Chart**: Stress levels among students.
- **Line Graph**: Relationship between sleep hours and stress levels.
- **Bar Charts**:
  - GPA distribution across study hours.
  - GPA distribution across physical activity hours.
- **Scatter Plot**: Correlation between study hours and GPA.
- **Combined Analysis**: Impact of multiple lifestyle factors on GPA.

---

## Key Insights

### Stress Levels:
- 51.4% of students experience moderate stress, while 14.8% face high stress.
- High stress correlates with insufficient sleep (<6 hours).

### Study Hours:
- Students studying over 9 hours daily achieve higher GPAs.
- GPA improves steadily as study time increases.

### Sleep and GPA:
- Students sleeping 7–9 hours generally perform better academically.
- Less than 6 hours or over 12 hours of sleep negatively impacts GPA.

### Physical Activity and GPA:
- Moderate physical activity (3–6 hours/day) correlates with higher GPAs.
- Excessive physical activity (>9 hours/day) may slightly lower performance.

### Social Hours:
- Limited social interactions (2–4 hours/day) positively impact GPA.
- Excessive social hours show no significant academic benefits.

### Overall Lifestyle Balance:
- High-performing students balance study, sleep, and moderate physical activity.
- Students with low grades often exhibit imbalanced lifestyles, with insufficient study and excessive extracurricular activities.

---

## Recommendations

1. **Balanced Lifestyle**:
   - Encourage students to maintain:
     - 7–9 hours of sleep.
     - 3–6 hours of study daily.
     - Moderate physical activity (3–6 hours).

2. **Stress Management**:
   - Introduce programs focusing on:
     - Sleep hygiene.
     - Time management.

3. **Extracurricular Activities**:
   - Limit to 1–3 hours daily to avoid academic decline.

4. **Personalized Interventions**:
   - Tailor strategies for students based on their GPA group.

---

## Outcome

- Developed a comprehensive dashboard illustrating key insights into how lifestyle factors impact academic performance.
- Provided targeted recommendations to enhance students’ GPA and reduce stress through lifestyle adjustments and institutional support programs.
