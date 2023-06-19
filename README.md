**Lead Scoring Case Study**

**Problem Statement:**
An education company named X Education sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses.

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%.

Now, although X Education gets a lot of leads, its lead conversion rate is very poor. For example, if, say, they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone.

This project is being submitted  by following team members:
1. Anil Thakre
2. Atul Mani
3. Yamuna

**Solution Approach:**

For this case study we're going to use logistic regression model to predict whether the lead is going to convert or not. We will achieve this by giving a score to each prospect ID and base on a cut-off value, the prospect can be put in the bucket of HOT LEAD.

The steps involved for this case study are mentioned below:

1. Data Loading
2. Data Exploration and pre-preprocessing which will include following steps:
    a. Missing value handling
    b. Outlier handling
    c. Feature engineering
3. Model Building using statsmodel and VIF
4. Model Performance Evaluation using Probability Calibration, ROC Curve, Precision-Recall Curve
5. Final recommendation.

**Files Submitted:**
1. README file for information
2. Python commented file: Juputer Notebook.
3. Word File: Answer of all the questions asked by the company in the word document provided. (PDF format)
4. Presentation:  Present the analysis. (PDF format)
5. Summary File: The summary report of case study. (PDF format)
