# About the dataset

https://www.kaggle.com/datasets/tejashvi14/travel-insurance-prediction-data

Context

A Tour & Travels Company Is Offering Travel Insurance Package To Their Customers.
The New Insurance Package Also Includes Covid Cover.
The Company Requires To Know The Which Customers Would Be Interested To Buy It Based On Its Database History.
The Insurance Was Offered To Some Of The Customers In 2019 And The Given Data Has Been Extracted From The Performance/Sales Of The Package During That Period.
The Data Is Provided For Almost 2000 Of Its Previous Customers And You Are Required To Build An Intelligent Model That Can Predict If The Customer Will Be Interested To Buy The Travel Insurance Package Based On Certain Parameters Given Below.

Content

Age- Age Of The Customer
Employment Type- The Sector In Which Customer Is Employed
GraduateOrNot- Whether The Customer Is College Graduate Or Not
AnnualIncome- The Yearly Income Of The Customer In Indian Rupees[Rounded To Nearest 50 Thousand Rupees]
FamilyMembers- Number Of Members In Customer's Family
ChronicDisease- Whether The Customer Suffers From Any Major Disease Or Conditions Like Diabetes/High BP or Asthama,etc.
FrequentFlyer- Derived Data Based On Customer's History Of Booking Air Tickets On Atleast 4 Different Instances In The Last 2 Years[2017-2019].
EverTravelledAbroad- Has The Customer Ever Travelled To A Foreign Country[Not Necessarily Using The Company's Services]
TravelInsurance- Did The Customer Buy Travel Insurance Package During Introductory Offering Held In The Year 2019.

## Objectives
The main objective of this project is to build a model that would correctly classify individuals into 2 categories: Those that want to buy extra travel insurance and those that do not.

Our main goal is to make sure that model correctly identifies as many individuals as possible who want travel insurance, so that a sales person (or algorithm) could do an offer. 

In other words we are interested quite much in recall of positive cases (individuals that want insurance) and less in precision. Precision is not as important due to an assumption that there is no harm in offering an insurance product to a person who doesn't need that product. The customer can just say "no" without to much negative emotions. 

## Results

- Best performing, Random Forest Regression, model achieved 79% ROC_SCORE, >80% recall and precision
- Recall for positive labels (individuals that want travel insurance) was 61% on test set
- Combined Recall for all labels was 84%. 
- If every customer matters, then we should look at 61% recall. If not - 84% recall is more appropriate

## Contents
This project contains the main 'project.ipynb' file which contains all the analysis performed on the travel insurance dataset. The project is divided into few main parts:
- Exploratory Data Analysis
- Feature engineering
- Modelling
- Conclusions 
- Limitations


