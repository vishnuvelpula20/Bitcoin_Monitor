# Bitcoin_Monitor

Batch Processing
Bitcoin Monitor
This ETL pipeline pulls Bitcoin exchange data from CoinCap API and loads it into our data warehouse.

## Architecture
We use Python to pull, transform, and load data. Our warehouse is Postgres. We also spin up a Metabase instance for our presentation layer.
All of the components are running as docker containers.
Architecture:

<img width="912" alt="bc_arch" src="https://github.com/user-attachments/assets/7609613f-0a4a-4f01-b5cc-8b82f65766a7">
