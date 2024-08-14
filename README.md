# Twitter Survey Analysis

This project analyzes the relationship between personality traits, particularly those assessed through surveys and MBTI (Myers-Briggs Type Indicator), and Twitter usage patterns. The analysis leverages both survey data and a large dataset of Twitter activity to explore correlations between perceived personality traits and online behavior.

## Project Objectives

- **Survey Data Analysis:** Understand how self-perceived personality traits, such as extraversion and neuroticism, correlate with Twitter usage, including the number of followers, tweets per day, and engagement levels.
- **Twitter MBTI Data Analysis:** Examine the relationship between MBTI personality types and Twitter activity across approximately 8,000 users.

## Methodology

1. **Data Collection:**
   - **Survey Data:** Collected responses on self-perceived personality traits and analyzed their correlation with various Twitter usage metrics.
   - **Twitter MBTI Data:** Extracted data on followers count, friends count, retweet length, and other parameters for 8,000 users.

2. **Data Preprocessing:**
   - Cleaned and prepared the datasets for analysis by handling missing values and encoding necessary features.
   - Merged and aligned data from different sources for consistency.

3. **Analysis:**
   - Conducted exploratory data analysis (EDA) to identify trends and correlations.
   - Applied statistical tests and visualization techniques to interpret the relationships between personality traits and Twitter usage.

## Key Findings

### Survey Data Findings:
1. Individuals who believe they are extraverted tend to have higher Twitter usage, marked by more followers, more tweets per day, and increased engagement with others.
2. Neuroticism showed little to no correlation with high Twitter usage.

### Twitter MBTI Data Findings:
- Despite analyzing the Twitter activity of approximately 8,000 users, no clear trend was found between the 16 MBTI personality types and Twitter usage.

### Divergence between Survey Data and Twitter MBTI Data:
- **Scope and Nature of Data Collection:** The survey data, collected at a specific time point, reflects static self-perceptions, whereas Twitter data represents ongoing user behavior.
- **Sample Representativeness:** The survey may have targeted a specific subset of the population, while the Twitter data spans a broader demographic.
- **Subjectivity vs. Objectivity:** Survey responses are subject to personal biases, whereas Twitter data provides objective metrics.
- **Personal Bias:** There may be discrepancies between MBTI designations and actual online behavior due to personal bias or the dissonance between belief and behavior.

## Inference from Results

The analysis suggests that while self-reported personality traits, particularly extraversion, correlate with increased Twitter usage, the MBTI personality types do not show a consistent pattern with online behavior. This highlights the complexities of personality assessments and the potential differences between perceived and actual behaviors.

## Future Developments

1. **Unified Methodology:** Future research should aim to harmonize data collection methods across self-report surveys and behavior-driven sources.
2. **Broader Demographics:** Ensuring that samples reflect the broader demographics of the Twitter user base could yield more generalizable results.
3. **Longitudinal Studies:** Tracking the same group of individuals over time could provide deeper insights into the dynamic relationship between personality and online behavior.

## Tools and Libraries

- **Pandas:** For data manipulation and cleaning.
- **Matplotlib & Seaborn:** For data visualization.
- **Scikit-learn:** For statistical analysis and modeling.
- **NumPy:** For numerical computations.

## How to Run

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/TwitterSurveyAnalysis.git
    cd TwitterSurveyAnalysis
    ```

2. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the notebook**:
    Open the `TwitterSurveyAnalysis.ipynb` notebook and execute the cells to follow the analysis.

## Conclusion

This project provides valuable insights into the relationship between personality traits and online behavior. The contrasting results from survey data and Twitter MBTI data underscore the importance of considering multiple factors and methodologies when interpreting personality and behavioral patterns.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
