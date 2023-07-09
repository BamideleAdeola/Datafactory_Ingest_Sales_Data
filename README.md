# Datafactory_Ingest_Sales_Data
Microsoft Fabric includes Data Factory capabilities, including the ability to create pipelines that orchestrate data ingestion and transformation tasks.
# Skills used in this exercise:
- Created a workspace
- Create a lakehouse
- Describe pipeline capabilities in Microsoft Fabric
- I used the Copy Data activity in a pipeline
- I created a pipeline based on predefined templates
- Run and monitor pipelines
- Modify the pipeline

- copy data into lakehouse
<img width="890" alt="pipeline1" src="https://github.com/BamideleAdeola/Datafactory_Ingest_Sales_Data/assets/54434309/ac9f5163-52e2-4d09-a542-244cde433908">

- Copy data into lakehouse using HTTP
<img width="893" alt="pipeline2" src="https://github.com/BamideleAdeola/Datafactory_Ingest_Sales_Data/assets/54434309/5b755ad8-b1b0-404d-85be-cfae0bdb0c50">

-Use the GET Request Method to connect to datasource:
<img width="899" alt="pipeline3" src="https://github.com/BamideleAdeola/Datafactory_Ingest_Sales_Data/assets/54434309/4edd91dc-9654-4bb9-87ce-674173e438f9">

- Selecting delimeters
<img width="902" alt="pipeline4" src="https://github.com/BamideleAdeola/Datafactory_Ingest_Sales_Data/assets/54434309/e419af21-f8ca-4373-8832-e447f706f802">

- Preview the data
<img width="827" alt="pipeline5" src="https://github.com/BamideleAdeola/Datafactory_Ingest_Sales_Data/assets/54434309/37468867-997a-49c1-b24d-d50cb5fb3aaa">

- Save and run
<img width="775" alt="pipeline6" src="https://github.com/BamideleAdeola/Datafactory_Ingest_Sales_Data/assets/54434309/d9a9d9e5-a99c-4df1-9d5f-378728e449e5">

- Output of the copy task
<img width="914" alt="pipeline7" src="https://github.com/BamideleAdeola/Datafactory_Ingest_Sales_Data/assets/54434309/030c2702-1174-4aa7-94f2-36ac4bf03799">

- Create a delete pipeline that connects the copy activity on completion
<img width="908" alt="pipeline8" src="https://github.com/BamideleAdeola/Datafactory_Ingest_Sales_Data/assets/54434309/7f384c6b-43b8-4b45-a80c-ddc9b8321bf5">

- Modify the delete activity as seen below:
<img width="902" alt="pipeline9" src="https://github.com/BamideleAdeola/Datafactory_Ingest_Sales_Data/assets/54434309/b588fd50-9fdd-4bb2-ac97-3cc6213e3023">
<img width="880" alt="pipeline10" src="https://github.com/BamideleAdeola/Datafactory_Ingest_Sales_Data/assets/54434309/3e23a91a-e3ce-4779-8809-480aec95c63d">
<img width="823" alt="pipeline11" src="https://github.com/BamideleAdeola/Datafactory_Ingest_Sales_Data/assets/54434309/79a616ee-f0fc-4edd-ada5-183318559b25">

- Create a notebook based on the data wrangled and update the parameter :
<img width="895" alt="pipeline13" src="https://github.com/BamideleAdeola/Datafactory_Ingest_Sales_Data/assets/54434309/1dd7aa86-b15c-47e4-9fc8-4f9d4439a6cb">

- Run and confirm that the activities run properly:
<img width="911" alt="pipeline14" src="https://github.com/BamideleAdeola/Datafactory_Ingest_Sales_Data/assets/54434309/38c24b90-0029-457c-a3ff-78359b8b1f87">

