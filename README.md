# SCCU_S25_CAPSTONE
This capstone project is for optimizing Logistics with Data-Driven Threshold Strategy.


## Business problem & Project objective

SCCU(Swire Coca-Cola United States) tries to optimize logistics by transitioning customers selling below a specific annual volume to an Alternate Route to Market (ARTM).
SCCU currently uses a 400-gallon annual volume threshold to determine whether customers should be assigned to:


- DDR (Direct Delivery Route)
- ARTM (Alternate Route to Market)

However, SCCU seeks a more cost-efficient and data-driven threshold that improves logistics efficiency and revenue performance.

## Solution to the business problem

This analysis will focus on building the classification model to predict which customer is going to be a growth customer segment (those who were below the threshold from 2023 but becoming above the threshold on following year (2024)) based on the 2023 historical data only, and determine which volume threshold would be more optimal compared to original (400) threshold.

- Predicts “growth potential customers” who were below the 400-gallon threshold in 2023 but surpassed it in 2024.
- Recommends an optimized volume threshold to improve decision-making for ARTM vs. DDR classification.

## My contribution to the project

1. Set up machine learning pipeline and data preprocessing workflow
2. Loading the dataset and checkout data profile
3. Measured benchmark performance using the existing 400-gallon threshold
4. Built and fine-tuned classification models to predict growth customers
5. Engineered and selected relevant variables & features
6. Evaluated models and selected the best-performing one
7. Compared operational performance between the existing and optimized thresholds

## The business value of the solution

- Cost Efficiency: Reduced delivery costs through optimized route assignments
- Operational streamlining: Better driver utilization, minimized travel time, and timely deliveries
- Strategic Decision-Making: 	Insights support inventory planning, fleet usage, and resource allocation
- Competitive Advantage: 	Streamlined operations lead to better service and market advantage

## Difficulties that encountered

These are the list of main challenges that our team had met while working on the project.

- Aligning different analytical perspectives on the identical business problem
- Ensuring data quality consistency across the ML pipeline
- Translating analytical insights into business value that operations teams can act upon

## What learned in the project

Out of S25 capstone project, I've learned the valuable lessons below.

- SCM decisions can be significantly improved using predictive analytics and data modeling
- A successful data project starts with a clear understanding of the business problem and follows a systematic, collaborative approach

## Tools/Skill that used in the project

- Python Pandas, Sklearn, Pickle, Seaborn
- R tidyverse, ggplot
- Deepnote.com, Colab, Canva, and Microsoft Suites
