# One-Way-ANOVA-Test

### Project Overview

  The goal of this project is to make more confident recommendation about which TV promotion type will result in the most sales revenues, using a historical marketing promotion data for a small business company.
  
### Business Understanding

  The company stakeholders wants to know if sales are significantly different among various TV promotion types, to make sure they are taking the right decision regarding their investment plans in the "high" TV promotion type. 


### Data Understanding

 This project uses a dtaset called marketing_sales_data. It represents the amount of money spent on TV, radio, and social media promotions, as well as the corresponding sales. It is a fictional dataset that was created for learning purposes and made available on Kaggle.

  
### Modelling and Evaluation
  
  The plot below shows differences in sales revenues per each TV promotional types.
  
  <img width="220" alt="image" src="https://github.com/aliMohamed-Z/One-Way-ANOVA-Test/assets/75675790/06c0c71d-ac79-4ff3-a0a1-e044d09d7f9d">


### Conclusion

  The F-test statistic is 1971.46 and the p-value is  8.81∗10−256 (i.e., very small). Because the p-value is less than 0.05, you would reject the null hypothesis that there is no difference in Sales based on the TV promotion budget.

  High TV promotion budgets result in significantly more sales than both medium and low TV promotion budgets. Medium TV promotion budgets result in significantly more sales than low TV promotion budgets.

Specifically, following are estimates for the difference between the mean sales resulting from different pairs of TV promotions, as determined by the Tukey's HSD test:

Estimated difference between the mean sales resulting from High and Low TV promotions: $208.81 million (with 95% confidence that the exact value for this difference is between 200.99 and 216.64 million dollars).
Estimated difference between the mean sales resulting from High and Medium TV promotions: $101.51 million (with 95% confidence that the exact value for this difference is between 93.69 and 109.32 million dollars).
difference between the mean sales resulting from Medium and Low TV promotions: $107.31 million (with 95% confidence that the exact value for this difference is between 99.71 and 114.91 million dollars).
