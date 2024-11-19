# Lead-Score-Case-Study-X-Education

## Problem Statement

An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses.

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos.

X Education gets a lot of leads, its lead conversion rate is very poor at around 30%

X Education wants to make lead conversion process more efficient by identifying the most potential leads, also known as Hot Leads

Their sales team want to know these potential set of leads, which they will be focusing more on communicating rather than making calls to everyone.

If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone. A typical lead conversion process can be represented using the following funnel:

![image](https://github.com/user-attachments/assets/6bfaf7de-ba20-4746-952a-125be615ad1c)

## Data

X-Education has provided a leads dataset from the past with around 9000 data points. This dataset consists of various attributes such as Lead Source, Total Time Spent on Website, Total Visits, Last Activity, etc. which may or may not be useful in ultimately deciding whether a lead will be converted or not.

The target variable, in this case, is the column ‘Converted’ which tells whether a past lead was converted or not wherein 1 means it was converted and 0 means it wasn’t converted.

## Goals of the Case Study

There are quite a few goals for this case study:

1. Build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.
2. There are some more problems presented by the company which your model should be able to adjust to if the company's requirement changes in the future so you will need to handle these as well. These problems are provided in a separate doc file. Please fill it based on the logistic regression model you got in the first step. Also, make sure you include this in your final PPT where you'll make recommendations.

## Problem Approach

-   Data Cleaning: Loading Data Set, understanding & cleaning data
-   EDA: Check imbalance, Univariate & Bivariate analysis
-   Data Preparation: Dummy variables, test-train split, feature scaling
-   Model Building: RFE for top 15 feature, Manual Feature Reduction & finalizing model
-   Model Evaluation: Confusion matrix, Cutoff Selection, assigning Lead Score
-   Predictions on Test Data: Compare train vs test metrics, Assign Lead Score and get top features
-   Recommendation: Suggest top 3 features to focus for higher conversion & areas for improvement

## Documentation

The current repositary consist follwing files and folders

-  **Data folder** - It consists of original data set and data dictionary file.
-  **Python file** - A python jupyter file which is added with the solution to the problem statement.
-  **Summary** - A pdf file consists with summary of explaining procedure solving the assignment and gathered learnings.
-  **PPT** - A pdf file consists with overall approach of the analysis in a presentation.
-  **Subjective Questions** - A pdf file filled with solutions to all the problems asked by X-Education.
