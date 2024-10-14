# Bitcoin_Monitor

Batch Processing
Bitcoin Monitor
This is an ETL pipeline to pull bitcoin exchange data from CoinCap API and load it into our data warehouse.
* [Bitcoin Monitor](#bitcoin-monitor)
    * [Run Data Pipeline](#run-data-pipeline)
    * [Architecture](#architecture)

# Bitcoin Monitor

This is an ETL pipeline to pull bitcoin exchange data from [CoinCap API](https://docs.coincap.io/) and load it into our data warehouse.
## Architecture
We use python to pull, transform and load data. Our warehouse is postgres. We also spin up a Metabase instance for our presentation layer.
All of the components are running as docker containers.
Architecture:

<img width="912" alt="bc_arch" src="https://github.com/user-attachments/assets/7609613f-0a4a-4f01-b5cc-8b82f65766a7">
