# Incremental-Pipeline
Incremental Load that works on "latest date based loading" and "ID(primary key based loading)"

This is automated Metadata Driven pipeline created in Azure Synapse workspace used for daily loading the increment data into the ADLSGen2 from cloud to cloud platform. 

Data used and cloud servers used in this pipeline are
# Metadata Driven Pipeline
Created Metadata table and load the tables into metadata table.

Used the metadata to load all the tables data into pipeline.
# Dataset and Cloud storage used
Dataset: CSV or it can be changed to required dataset
Storage Account: ADLSGEN2
Source Data: Azure SQL Database
Loaded the data into ADLSGEN2 from the Azure SQL Database

Integration Runtime: Auto Resolve integration run time
This integration runtime is used to copy data from cloud to cloud which is provided by Azure by default 

Document is Attached in this file for the reference.
