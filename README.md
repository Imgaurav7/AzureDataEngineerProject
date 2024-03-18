# AzureDataEngineerProject


In this project, we're using a regular database called SQL Server that's kept within the company instead of using a cloud-based one. We have about six or seven sets of data in this database. We're moving all of this data to the cloud using a tool called Azure Data Factory. This tool helps copy all the data from our regular database and move it to the cloud. We're storing this data in a place called Azure Data Lake Gen2.

Once the data is in Azure Data Lake, we're using another tool called Azure Databricks to make the data better. Azure Databricks helps us change the raw data into something more useful. It's like polishing raw material into something shiny and valuable.We have used lake house architecture for this project means We're organizing the data into different layers, like bronze, silver, and gold.

Imagine the bronze layer as the first step where we copy the data from our regular database without changing anything. It's like taking a photo of the data as it is. We're not touching this data, just keeping it as it is. This is helpful because if something goes wrong later, we can always go back to this photo and see how the data originally looked.

Then, using Azure Databricks, we're making some small changes to the data in the silver layer. These changes could be things like renaming columns or adjusting data types to fit better in the cloud. It's like making minor adjustments to improve the data quality.

Finally, we're doing more significant changes in the gold layer. This is where the data is in its cleanest and most useful form. It's like getting the final polished version of the data ready to be used for important tasks.
