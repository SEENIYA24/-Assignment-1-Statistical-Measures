# -Assignment-1-Statistical-Measures
Statistical measures are numerical values derived from data to summarize, describe, and interpret characteristics of that data. They provide insight into the central tendency, dispersion, correlation, and overall structure of a dataset. 
    Measures of Central Tendency: Indicate the center or typical value in a dataset.
        Mean: Average of all data points.
        Median: Middle value when data is sorted.
        Mode: Most frequently occurring value.

    Measures of Dispersion: Show how spread out or variable the data points are.
        Range: Difference between the maximum and minimum values.
        Variance: Average of squared deviations from the mean.
        Standard Deviation: Square root of variance, representing average distance from the mean.

    Measures of Shape: Describe the distribution's symmetry and tail weight.
        Skewness: Indicates asymmetry. Positive skewness shows a right-tailed distribution, and negative skewness shows a left-tailed one.
        Kurtosis: Indicates the "tailedness" or presence of outliers. High kurtosis means heavy tails (more outliers).

    Measures of Association: Describe relationships between variables.
        Correlation Coefficient (Pearson’s): Quantifies the strength and direction of a linear relationship between two variables, ranging from -1 to 1.
        Covariance: Indicates the direction of the linear relationship between two variables but not the strength.

Findings and Conclusions

Based on the steps you performed, here are some conclusions that could be drawn:

    Outlier Management:
        After trimming and capping the price_per_sqft column, you observed a reduction in extreme values. This helps in creating a more robust dataset that reduces the influence of outliers on the mean and other statistics.
        Box plots confirmed which approach (capping or trimming) was more effective at reducing the impact of extreme values.

    Normality of price_per_sqft:
        The initial skewness and kurtosis suggested that price_per_sqft was not normally distributed.
        A log transformation or other adjustments may have helped bring the distribution closer to normality, indicated by reduced skewness and kurtosis values.

    Correlation Analysis:
        The correlation heatmap revealed which numerical variables had strong positive or negative relationships. High positive correlations suggest that as one variable increases, another tends to increase as well.
        Scatter plots helped visualize these relationships, confirming the correlations found in the heatmap and providing insights into potential linear relationships between price_per_sqft and other numerical variables.

    Interpretations of Skewness and Kurtosis:
        High skewness indicated that the original distribution of price_per_sqft was asymmetrical, often pointing to a concentration of values on one side of the mean.
        High kurtosis in the original data suggested more extreme outliers, which might impact mean and variance estimates if not managed.

Concluding Insights

    Data Quality: Outlier handling, such as capping or trimming, improved the overall quality of price_per_sqft data, creating a cleaner dataset for analysis.
    Data Normalization: Applying transformations reduced skewness and kurtosis, which is valuable if further analyses assume normality, such as certain regression models.
    Relationships: Correlation and scatter plots provided insights into which features are related, helping to identify potential predictive variables for price_per_sqft.

These insights enhance understanding and support decision-making in areas such as pricing models, predictions, and data-driven strategies.
