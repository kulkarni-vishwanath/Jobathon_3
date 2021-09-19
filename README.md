![cover_companies_update_4_eDZEesQ-thumbnail-1200x1200](https://user-images.githubusercontent.com/25604111/133938497-52557cc6-3508-4908-909b-92501aaa3d6a.png)


# JOB-A-THON
This repo contains the code and approach document related to JOB-A-THON conducted by Analytics Vidhya.
Link to Competition [here](https://datahack.analyticsvidhya.com/contest/job-a-thon-september-2021/).

## Problem Statement
Your Client WOMart is a leading nutrition and supplement retail chain that offers a comprehensive range of products for all your wellness and fitness needs. 

WOMart follows a multi-channel distribution strategy with 350+ retail stores spread across 100+ cities. 

Effective forecasting for store sales gives essential insight into upcoming cash flow, meaning WOMart can more accurately plan the cashflow at the store level.

Sales data for 18 months from 365 stores of WOMart is available along with information on Store Type, Location Type for each store, Region Code for every store, Discount provided by the store on every day, Number of Orders everyday etc.

**Your task is to predict the store sales for each store in the test set for the next two months.**


## Data Dictionary

| __Variable__ | __Description__ |
|-------------|------------|
| ID          | Unique Identifier for a row     |
| Store_id         | Unique id for each Store |
| Store_Type |Type of the Store |
| Location_Type | Type of the location where Store is located |
| Region_Code | Code of the Region where Store is located |
| Date | Information about the Date |
| Holiday | If there is holiday on the given Date, 1 : Yes, 0 : No |
| Discount | If discount is offered by store on the given Date, Yes/ No |
| #Orders | Number of Orders received by the Store on the given Day |
| Sales | Total Sale for the Store on the given Day |


## Evaluation Metric
The evaluation metrics for this competition is MSLE*1000.

## Leaderboard
**Public Leaderboard:** 66/1017: 

**Public LB Score:** 208.277653270504

**Private Leaderboard:** 214/1017

**Private LB Score:** 239.544729500494

