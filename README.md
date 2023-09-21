# ETL-Data-Pipeline-on-GCP-for-Uber-Data-analytics
## 1-Introduction
The goal of this project is to perform data analytics on Uber data using various tools and technologies, including GCP Storage, Python, ComputeEngine, Mage Data Pipeline Tool, BigQuery, and Looker Studio.

## 2-Architecture
![ETL GCP  - Page 3](https://github.com/hafsaelgha/ETL-Data-Pipeline-on-GCP-for-Uber-Data-analytics/assets/99973359/78b0e7ea-f498-48ab-8ac8-fa055dde08f3)
- [ ] GCS : google cloud storage is a fully managed object storage that use stores objects into bucket. We can define the storage class, (standard in our case), the location type (multi-region),the ACL (public access), the uploads type… 
- [ ] Compute engine : it’s a virtual machine provided by Google Cloud to host our services, we changed its configuration depending on our use case (see section below).
- [ ] Mage : is a modern data tool created by an Ex Airbnb Engineer, which aims to be a competitor of Airflow but with more advanced services for data pipeline and with a nice UI which make it an easy cool modern tool ! 
- [ ] BigQuery : its a petabyte scale analytics data warehouse that allows us to execute fast SQL queries across large datasets.
- [ ] Looker Studio : free tool that turns your data into informative, easy to read, easy to share, and fully customizable dashboards and reports.


## 3-Data Dimensional modelling
![data dimensional modeling ](https://github.com/hafsaelgha/ETL-Data-Pipeline-on-GCP-for-Uber-Data-analytics/assets/99973359/a37510c8-3fbe-4f39-b726-e4cb54a13add)

## 4-Steps and Remarks 
### I will include errors to avoid during this project too ! 
### Storage on GCS
Converting from parquet file to csv file and store it on google cloud storage.
The Parquet format is based on a columnar structure, which means that data is organized in columns rather than rows. This allows for efficient data compression and better resource utilization when executing queries.
![object ](https://github.com/hafsaelgha/ETL-Data-Pipeline-on-GCP-for-Uber-Data-analytics/assets/99973359/678293e7-2859-4f1b-8800-4881caca399c)
**About Configuration of your bucket** : 
**Public API Object** : to extract data from it as a **public API** by using it’s URL.

### Compute Engine 
See the basic configuration I used for my instance : 
![VM basic info](https://github.com/hafsaelgha/ETL-Data-Pipeline-on-GCP-for-Uber-Data-analytics/assets/99973359/597475c4-b6cb-4e9c-9344-541453cc87d1)
![VM config](https://github.com/hafsaelgha/ETL-Data-Pipeline-on-GCP-for-Uber-Data-analytics/assets/99973359/fa05ac9c-83e1-40a7-8c47-facf9d885ea1)






