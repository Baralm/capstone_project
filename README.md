# Problem Statement
---
Analyse the Kickstarter data and apply the Machine Learning concept to build the model that can predict whether or not the kickstarter project was successful.


# Executive Summary
---
Kicstarter supports and hosts a global crowdfunding platform to harbour and encourage creative projects and startups specifically for creative projects in the following categories: Art, Comics, Crafts, Dance, Design, Fashion, Film & Video, Food, Games, Journalism, Music, Photography, Publishing, Technology, and Theater.  Kickstarter follows an all-or-nothing funding model which means is that if the project does not gather funds (a total pledged amount) equal to or greater than the goal amount by the project deadline, the pledged amount(if any) is not charged from the backers and the project creators are not expected to complete the project in whatever amount that has been pledged so far. So it is important to understand about the important atrributes to make the project successful. I obtained the kickstarter dataset from kaggle with 12 explanatory variables (attributes).

# Data Dictionary
---
The data given are:
- ks-projects-2016
- Click This for  <div style="direction:rtl">
    <a href="https://www.kaggle.com/kemical/kickstarter-projects#ks-projects-201612.csv">Data Dictionary</a>
</div> 

# Method
---
- Import and check the data
- Identify data types and missing values
- Handle missing values and clean the data
- Create charts and graphs to identify trends
- Evaluate the predictors and build a model
- Check the performance of the model
- Evaluate the model

# Conclusion
---
### Model
- Gradient Boosting Classifier
 - Train Accuracy score : 0.93
 - Test Accuracy Score: 0.929
 - Precision: 0.92
 - Recall: 0.90
 - AUC-ROC curve: 0.98

# Recommendation
---

Algorithm has given the most important features as backers and it makes sense as Kickstarter has adopted All-or-nothing funding meaning that no one will be charged for a pledge towards a project unless it reaches its funding goal and to make project successful it needs backers to support and share about the project (word-of-mouth)







