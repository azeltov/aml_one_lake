# AML and OneLand and Fabric Better Together Demo:
You can use OneLake's capability to create shortcuts within a Lakehouse to read and write data stored in Azure Data Lake Gen2. Since Azure Machine Learning supports Azure Data Lake Gen2 storage, this setup allows you to use Fabric and Azure Machine Learning together. The data architecture is as follows:

![image](https://github.com/azeltov/aml_one_lake/assets/5873303/51c5babd-843b-44d5-af43-2ee74043ae59)

Follow the "Configure data access" section in the article  to setup onelake and access before running the notebook: 

https://learn.microsoft.com/en-us/azure/machine-learning/how-to-use-batch-fabric?view=azureml-api-2

My one-lake setup look like this:

![image](https://github.com/azeltov/aml_one_lake/assets/5873303/7945ea31-c6a2-4d28-95ac-445206bb6fca)

copy the url , you will need this to customize in your notebook:

https://onelake.dfs.fabric.microsoft.com/amldemo/amlsilver.Lakehouse/Files/data-aml

In the notebook you will need to plug in your onelake info in the cell like here:

![image](https://github.com/azeltov/aml_one_lake/assets/5873303/92c7c2d2-ccf6-4bbf-b6e7-34d4004ee260)



