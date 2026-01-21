# Workplace Stress Analysis in Canada

## Overview
This project analyzes workplace stress patterns across different demographic groups in Canada to identify which populations experience higher stress levels. The analysis uses statistical testing to examine relationships between age, gender, and reported workplace stress.

## Dataset
The dataset was obtained from **Statistics Canada** (provided through an official link by the course instructor). 

- **Processing**: One dataset was used, filtered to include only relevant variables for the analysis
- **Main Features**:
  - Gender
  - Age group
  - Occupation type
  - Reported stress levels (number of people reporting feeling stressed)

## Hypothesis
**Younger workers and women report higher levels of workplace stress compared to older workers and men.**

Significance Level: α = 0.05 (5% risk of Type I error)

## Key Findings

### Age-Based Analysis (ANOVA)
- **Result**: Very small p-value (< 0.05)
- **Interpretation**: Age group has a **statistically significant** effect on workplace stress levels
- **Conclusion**: Younger workers do report higher levels of work-related stress

### Gender-Based Analysis (T-Test)
- **Result**: p = 0.82
- **Interpretation**: No statistically significant difference between genders
- **Conclusion**: The difference in stress levels between men and women could have happened by random chance

### Hypothesis Outcome
✅ **Partially Supported**: The data confirms that younger workers experience higher workplace stress, but gender does not appear to be a significant factor in stress levels.

## Statistical Methods

### ANOVA (Analysis of Variance)
- **Purpose**: Test whether average stress levels vary significantly by age group
- **Why chosen**: Appropriate for comparing means across multiple groups (age categories)
- **Finding**: Confirmed significant differences between age groups

### T-Test
- **Purpose**: Compare average stress levels between men and women
- **Why chosen**: Appropriate for comparing means between two groups
- **Finding**: No significant difference detected (p = 0.82)

## Technologies Used
- **Python 3.x**
- **Pandas**: Data manipulation and filtering
- **NumPy**: Numerical computations
- **Matplotlib**: Data visualization
- **SciPy/Statsmodels**: Statistical testing (ANOVA, T-Test)
- **Jupyter Notebook**: Analysis environment

## How to Run
```bash
# Clone the repository
git clone https://github.com/hhcecilia/workplace-stress-analysis.git

# Navigate to project directory
cd workplace-stress-analysis

# Install required packages
pip install pandas numpy matplotlib scipy jupyter

# Launch Jupyter Notebook
jupyter notebook
```

## Project Insights

### What Worked
- Successfully identified age as a significant factor in workplace stress
- Statistical testing provided evidence-based conclusions
- Achieved the main goal of identifying which groups experience higher stress

### Limitations
The dataset lacked deeper context that could explain more variation in stress levels:
- Job role and industry information
- Income levels
- Access to mental health resources
- Working conditions (remote vs. on-site)

### Ideal Additional Data
- Mental health service access statistics (who had access vs. who didn't)
- Remote vs. on-site work arrangements
- Industry-specific information
- Socioeconomic indicators

## Key Learnings
If repeating this project, I would:
1. **Source a more detailed dataset** including variables like job role, industry, income, and mental health resource access
2. **Include more contextual factors** to build a more accurate model
3. **Expand analysis** to better explain stress variation across different workplace conditions

## Problem Resolution
The analysis successfully identified which demographic groups are more likely to experience workplace stress in Canada, addressing the primary research question.

## Author
**Heather Hallberg**  
Software Development Student | Health Tech Enthusiast  
[GitHub](https://github.com/hhcecilia) | [Email](mailto:heather.hb@hotmail.com)

---

*Project completed as part of Data Science coursework*
