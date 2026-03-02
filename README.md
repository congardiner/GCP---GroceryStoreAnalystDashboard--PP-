# Field Study of Convenience Store Data - Idaho (2022 - 2024) 

(Large Scale Data Analysis)

A client-server GCP application built with streamlit, SQL, python, and GCP. Displays convenience store transactions (credit, debit, and cash) and visualizes it using a centralized streamlit dashboard.  


## Tech Stack

- Python
- SQL
- Docker
- Databricks
- GCP
- Streamlit

## Reference Images of Personal Project

![Homepage of the Dashboard](images/streamlit-cstore-convenience-analytics-dashboard-01.png)

![Weekly Revenue Trend for the Top 5 Products Sold](images/streamlit-cstore-convenience-analytics-dashboard-02.png)

![Lowest Performing 10 Brands by Revenue (Historical)](images/streamlit-cstore-convenience-analytics-dashboard-03.png)

![Home Values & Income Distribution of Clients](images/streamlit-cstore-convenience-analytics-dashboard-04.png)

## Reference Links 

- GCP Cloud URL: https://app-challenge-fa25-387093992096.us-west3.run.app/ 


## Resolved Issues

- Streamlit dashboard and visualization charts were created to dictate isolated issues with representing a large-scale dataset with real-world convenience store data, as there are several pillars that were investigated as a result of this. 
- I've had no issues with cloning the repo, building the docker image, or deploying to GCP Cloud Run at this time of writing (I had a number of issues initially, as GCP was extremely cumbersome to use due to constant lagging and timeouts, after changing my yaml and the initial setup within GCP to accommodate for more memory and vCPUs, it has been smooth sailing since then).
