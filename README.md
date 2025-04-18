# SCCU_S25_CAPSTONE

## Business problem & Project objective

SCCU(Swire Coca-Cola United States) tries to optimize logistics by transitioning customers selling below a specific annual volume to an Alternate Route to Market (ARTM). There is an annual 400 gallons volume threshold used to distinguish the customers between the direct delivery route and ARTM.

However, SCCU is looking for a more cost-efficient strategy to decide new threshold for optimizing logistics which is driving better operational efficiency and more revenues.

## Solution to the business problem

This analysis will focus on building the classification model to predict who is going to be a growth customer segment (those who were below the threshold from 2023 but becoming above the threshold on following year (2024)) based on the 2023 historical data only, and which volume threshold would be more optimal compared to original (400) threshold.

Our analysis will meet to these missions:

- Identifying which customers should be included in ARTM versus DDR.
- Determining the optimal volume threshold to improve logistical efficiency.

## My contribution to the project

1. Setting up the ML pipeline classes
2. Loading the dataset and checkout data profile
3. Identifying the benchmark performance of original threshold
4. Genenrating the classification model to predict the growth customer group
5. Selecting and engineering the variables used in the modeling
6. Training and evaluating the performance between the models and select the best model
7. Generating the comparison metrics between new threshold and old threshold

## The business value of the solution

- Cost Efficiency: Reducing delivery cost and optimizing logistical transition directly lowers operational costs, improving profit margin
- Operational streamlining: Minimizes travel time, enhances driver productivity, and ensures timely deliveries, boosting overall logistics performance
- Strategic Decision-Making: Insights from fuel usage and route data enable better inventory management, fleet optimization, and proactive resource allocation
- Competitive Advantage: Lower costs and improved service reliability position the business ahead of competitors in the market

## Difficulties that encountered

These are the list of main challenges that our team had met while working on the project.

- Sync the different perspective about the problem itself and enabling teams be on the same page
- Consolidating and confirming the data quality across the steps of pipeline
- Connecting the analytical result with actual business values

## What learned in the project

Out of capstone project (S25), I've learned the valuable lessons in that
SCM (Supply Chain Management) domain can be operated and optimized systematically based on data driven decision making.
However, it is very significant to define the business problem specifically and approach the defined problem with 
