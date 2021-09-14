# Humana-Mays Data Science Competition

# Predicting Medicare Members Most Likely Struggling with Transportation Issues
Authors: Brian Bacik, Chiu-Feng Yap

#### Project Status: [Completed]

### Project Ranking: Top 50/276

# Introduction

Using 1-year worth of retrospective data of Humana MAPD members, competition participants are required to analyze the data to develop a predictive model that takes in a set of features of customers and assigns to each member a probability of being at risk for a transportation challenge. These probabilities will be evaluated by the ROC AUC paradigm, essentially measuring the ability of the model to correctly classify members. 

# Methods Used:
* Categorical variable encoding
* Feature engineering
* Hyperparameter tuning
* Dimension reduction

# Models Used:
* Logistic Regression Classifier
* Lasso Regression 
* Elastic Net
* Support Vector Machine
* Random Forest
* XGBoost Classifier

# Data Source 

Raw training data and the holdout set are provided by Humana. Data comes from various sources documenting members’ medical-related behaviors, including:

*	Medical claims
* Pharmacy claims
* Lab claims
*	Demographic/consumer data
* Credit card
*	Clinical condition related
*	CMS member data elements


# Target Variable

The target variable (transportation issue) is a self-reported binary variable (“0” - No, “1” - Yes) to indicate transportation challenges. Transportation screening question:

“In the past 12 months, has a lack of reliable transportation kept you from medical appointments, meetings, work, or getting things needed for daily living?” is coming from the Accountable Health Communities - Health-Related Social Needs Screening Tool. The survey was completed in November/December 2019. 

