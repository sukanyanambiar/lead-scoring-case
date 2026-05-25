# Lead Scoring Model — X Education

## Overview
X Education sells online courses to professionals but converts 
only ~30% of leads despite significant sales effort. The 
business goal: identify "hot leads" worth prioritising so the 
sales team focuses energy where conversion probability is highest.

Target set by CEO: lift conversion rate from 30% to 80%.

## Approach
- Cleaned and preprocessed lead-level data including source, 
  activity, and demographic variables
- Exploratory analysis to identify conversion patterns by 
  lead source, engagement behaviour, and profile
- Built a logistic regression model to score each lead 
  between 0-100
- Validated model against the 80% conversion rate target

## Key Findings
- Lead source and website engagement time were strongest 
  predictors of conversion
- Leads from certain referral sources converted at 
  significantly higher rates than organic/direct traffic
- Sales team was spending disproportionate time on 
  low-probability leads — model enables prioritisation

## Output
Every lead receives a score from 0-100. Leads above a defined 
threshold are flagged as hot leads for immediate sales follow-up, 
enabling the team to concentrate effort on the highest-probability 
conversions.

## Business Impact
Implementing score-based prioritisation projected to lift 
conversion rates toward the 80% CEO target by eliminating 
low-value outreach and focusing sales capacity on warm leads.

## Tools
Python, pandas, scikit-learn, logistic regression, 
matplotlib, seaborn

## Team
Group project — Sukanya Nambiar
