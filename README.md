## EDS - Domain Data Analytics
The Self-Service Data Analytics Platform is a unified platform built based on Data Mesh architecture style for ingestion, storage, processing, and analytics of source data to Snowflake based Data Warehouse. This is a metadata/configuration driven generic platform that can be customized for any domain needs without much intervention by the IT team.


### Data meash
A data mesh architecture is a decentralized approach that enables domain teams to perform cross-domain data analysis on their own. At its core is the domain with its responsible team and its operational and analytical data. The domain team ingests operational data and builds analytical data models as data products to perform their own analysis. It may also choose to publish data products with data contracts to serve other domains’ data needs.

<img src="https://user-images.githubusercontent.com/122434276/226250376-22a97d44-2b65-46c0-918b-1195101b5f8e.png" width=75% height=75% />

<br>

### Metadata driven pipeline
<img src="https://user-images.githubusercontent.com/122434276/226251773-1c37a63f-1abf-47ef-8d4b-6127924cafe2.png" width=75% height=75% />




<br>

---
## Platforms 

purpose/technology                | platform
:---------------------------------|:-----------------------------------
Cloud Platform                    | Azure                           
Data warehouse                    |  Snowflake (Mention Version)    
Orchestration                     | Azure Data Factory              
Source data pre-processing        | Azure Function                  
Email notification                |Azure LogicApps                  
Data Quality and business transformations                   | Snowpark Procedures             
Languages                         | Python/SQL                      
Version Control, CI/CD            | Git, SchemaChange, Terraform    

---

There are four folders on this repository,
* Documents
* Infra
* Scripts
* Source

---


