#       Telecom Churn Case Study

### Problem statement:


In telecom industry, acquiring a new customer is 5-10 times more expensive than retaining an existing customers. In South Asian markets, the companies have a huge customer base  who are on prepaid network and hence can move to another network without any prior notice/intimation. Therefore it is of great importance to telecom companies to identify the customers who are at high risk of leaving the network(i.e. getting CHURNED) so that the company can act(with promotional packages/discounts) before the customer actually leave them.   

### Objective: 

- The main purpose of this case study is to analyse at 3 months data(usage of various service of company like local, std, isd incoming outgoing calls, 2g and 3g network etc) and predict if the user shows at change in pattern indicating risk of him being churned. 
- The other objective of the case study is to identify the features in data  which have the major impact on the customer's churn probability. That will help the company to use their resource accordingly, in overall improvement in infra, to offer discounted services to high risk customers etc.

### Approach:

1. Reading and Understanding  Data
2. Data Cleaning
3. EDA
4. Data pre-processing for Modeling
5. Modeling
6. Final Model selection
7. Test predictions for submission
8. Inference Model
9. Summary

## Data Definitions:

The definitions are also listed down below:
- CIRCLE_ID : Telecom circle area to which the customer belongs to
- LOC : Local calls - within same telecom circle
- STD : STD calls - outside the calling circle
- IC : Incoming calls
- OG : Outgoing calls
- T2T : Operator T to T, i.e. within same operator (mobile to mobile)
- T2M : Operator T to other operator mobile
- T2O : Operator T to other operator fixed line
- T2F : Operator T to fixed lines of T
- T2C : Operator T to it’s own call center
- ARPU : Average revenue per user
- MOU : Minutes of usage - voice calls
- AON : Age on network - number of days the customer is using the operator T network
- ONNET : All kind of calls within the same operator network
- OFFNET : All kind of calls outside the operator T network
- ROAM : Indicates that customer is in roaming zone during the call
- SPL : Special calls
- ISD : ISD calls
- RECH : Recharge
- NUM : Number
- AMT : Amount in local currency
- MAX : Maximum
- DATA : Mobile internet
- 3G : 3G network
- AV : Average
- VOL : Mobile internet usage volume (in MB)
- 2G : 2G network
- PCK : Prepaid service schemes called - PACKS
- NIGHT : Scheme to use during specific night hours only
- MONTHLY : Service schemes with validity equivalent to a month
- SACHET : Service schemes with validity smaller than a month
- *.6 : KPI for the month of June
- *.7 : KPI for the month of July
- *.8 : KPI for the month of August
- FB_USER : Service scheme to avail services of Facebook and similar social networking sites
- VBC : Volume based cost - when no specific scheme is not purchased and paid as per usage

### Data files:

 Refer to #https://www.kaggle.com/competitions/telecom-churn-case-study-hackathon-c-69/overview - for more details of the problem statement and
  -   train.csv( 3month customer data, containing customer churn/not churned status in 4th month)
  -   test.csv(the customers for which churning proabability is to be predicted)
