# Bank Marketing Campaign Analysis
Objective: Identify customer profiles with the highest conversion rates for term deposits and provide actionable recommendations to improve campaign efficiency.
## Business Problem
The bank conducted marketing campaigns but needed to understand:

Which customer segments are most likely to subscribe
How to optimize campaign costs and effort
Where to focus future marketing efforts

## Dataset
Source: Bank Marketing Dataset - Kaggle

~11,000 records with customer demographics, financial data, and campaign outcomes.

## Tools Used
Python (pandas, numpy, matplotlib)
Jupyter Notebook

# Key Findings
## Best Converting Customer Profile
Age: Under 25 or over 65
Occupation: Management, technical, administrative roles  
Pensioners: 66% conversion rate — high-value segment for retention  
Balance: Customers with €1,700+ convert at 57% vs. 36% for those under €122  
## Untapped Opportunity
Blue-collar workers: Largest volume (1,944 clients) but only 36% conversion  
Potential for significant growth with targeted campaigns  
## Campaign Efficiency
First 3 contacts generate 86.6% of all conversions  
Calls after the 11th contact have minimal ROI — waste of resources  
## Critical Success Factor  
Clients with previous campaign success convert at 91%  
Re-contacting this segment should be Priority #1  

# Recommendations

## Priority	Recommendation	Expected Impact
1	Create a dedicated retention campaign for previously successful clients	- 91% conversion potential  
2	Develop targeted offers for blue-collar segment - Large untapped volume  
3	Cap contact attempts at 3-5 per client - Reduce costs, protect brand reputation  
4	Focus on balance-based segmentation - Prioritize €1,700+ clients  

# Next Steps
Build a predictive model to score lead probability  
A/B test different messaging for blue-collar segment  
Analyze cost-per-acquisition by contact method  

Built by Vlad Dvorshiv as part of a data analyst portfolio. Background in economics and statistics. Feedback welcome!



