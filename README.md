# ETL-Workflow-DEMO

## Objective:
ETL stands for *Extract-Transform-Load*, it usually involves moving data from one or more sources, manipulating the data, and then loading it into new single destination (data warehouse). In most companies, data tends to be in silos, stored in various format and is often inaccurate or inconssistent. This siutation is far from ideal if we want to be able to analyse and get insight from that data or use it for data science.

### Importance of Data Collection and Storage:

![Data Science](https://miro.medium.com/max/4800/0*X04nkVYoxrkdA9u2)

## Real-World ETL Example:

![ETL](https://miro.medium.com/max/1400/0*iURcj_v5E1RsJiyA)

### Extract:
This part of the process involves retrieving data from our two sources, SalesForce and Stripe. Once the data has been retrieved, the ETL tool will load it into a staging area in preparation for the next step.

### Transform:
This is a critical step, because it handles the specifics of how our data will be integrated. Any cleansing, reformatting, deduplication, and blending of data happens here before it can move further down the pipeline.

### Load:
This step involves successfully inserting the incoming data into the target database, data store, or in our case a data warehouse.
