# Community-And-Data-Driven_Homelessness_Prevention

This repository holds OOS counterfactual predictions based on the BART model described in ____________

## Attribution
If you plan to use this data, we ask that you cite the following paper:

_______________________

Which can be found here: ______________________

## Description of the Data
The csv file contained in this repository consists of ___ rows and ___ columns. Each row represents a homeless household. 
The variable named Original represents the homeless service the household was assigned to by caseworkers (the factual allocation). 

The variable named Outcome has two potential values, 1 or 0. A value of 1 indicates that the household was in need of more homeless services within 2 years after exiting the system. A value of 0 indicates no need for services within those 2 years (the ideal outcome). 

The columns labeled ES, TH, RRH, and Prev give the counterfactual prediction for whether that household would need services again within 2 years if they had been allocated to that intervention. ES stands for Emergency Shelter, TH Transitional Housing, RRH Rapid Rehousing, and Prev stands for Homelessness Prevention. Couterfactual predictions are calculated using BART, as described in detail in the paper referenced above.

The variable named PrevEligible is an indicator of whether (1) or not (0) a household is eligible to receive prevention services. This indicator is calculated using information about a household's previous residence and current housing situation. If a household is not eligiable to recieve prevention, a prediction for probablity of reentry if that household is placed in prevention is not provided.

