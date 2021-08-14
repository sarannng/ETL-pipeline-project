# ETL-pipeline-project
During internship with cognizant developed a demo ETL pipeline to transform the data from csv source to Azure SQL database using Azure Data Factory

##Key points
- Store the data in Azure blob storage inside an input container.
- Use Azure SQL database for the DW.
- Create the SQL server and username with reference to linked service keys mentioned in DDL file.
- Import the ARM templete and test all the connections with datasets once.
- Make sure that Integration runtime is managed by azure. 
- Check that Identity insert is on in DW.
