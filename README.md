# Project Title:
- Analyzing Customer Purchase Behavior at Walmart Based on Gender and Marital Status on Black Friday using Central Limit Theorm. 

# Problem Statement:
- Walmart Inc. wants to understand if there are significant differences in spending behavior on Black Friday based on customer gender and marital status. Specifically, the management seeks to answer the question:

## Do women spend more than men on Black Friday?
- Given that Walmart has over 100 million customers worldwide, with an equal distribution between male and female customers (50 million each), the goal is to use sample data to make inferences about the overall population.

# Approach:
## Data Collection:

- Gather sample data on purchase amounts, gender, and marital status for Walmart customers on Black Friday.
- The sample should represent both male and female customers, ensuring a sufficient sample size to capture the diversity of spending patterns.
Central Limit Theorem (CLT) Application:

- According to the Central Limit Theorem, the sampling distribution of the sample mean approaches a normal distribution as the sample size increases, regardless of the population's distribution.
- Using a sufficiently large sample size (for example, 1,000 males and 1,000 females), we can estimate the population mean and infer whether there is a significant difference in spending between men and women.
- Assume normality of the sample means due to the large sample sizes, and use this to make inferences about the population means for male and female spending.
Hypothesis Formulation:

- Null Hypothesis (H₀): There is no difference in the average spending on Black Friday between male and female customers (mean spending by males = mean spending by females).
- Alternative Hypothesis (H₁): Women spend more on Black Friday than men (mean spending by females > mean spending by males).
## Statistical Test:

- Conduct a two-sample t-test (since we are comparing means between two independent groups: male and female customers).
The significance level (𝛼) is set at 5%, meaning that we will reject the null hypothesis if the p-value is less than 0.05.
### Confidence Interval:

- Use a 90% or 95% confidence interval to estimate the difference in average spending between males and females. This will help quantify the difference in spending and assess its practical significance.
## Conclusion:

- Based on the t-test results, if the p-value is less than 0.05, we reject the null hypothesis and conclude that women spend significantly more on Black Friday than men.
- If the p-value is greater than 0.05, we fail to reject the null hypothesis, suggesting no statistically significant difference in spending behavior between genders.
## Business Insight:

- If a significant difference is found, the business can tailor marketing strategies to target high-spending groups (e.g., offering specific promotions to female customers or analyzing further to understand purchasing patterns by marital status).
- If no significant difference is found, Walmart can focus on other demographic or behavioral factors to drive sales and improve customer targeting.
## Deliverables:
- A report that includes statistical analysis results, hypothesis testing, confidence intervals, and recommendations based on findings.
- Visualizations of spending behavior differences by gender and marital status.
- Actionable insights for Walmart's management team to optimize marketing strategies for future Black Friday events.
