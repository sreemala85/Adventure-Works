
# Project Architecture
<img width="992" height="325" alt="image" src="https://github.com/user-attachments/assets/57314855-841d-4776-87d9-2c3e0cf68ba8" />

# Overview of the Project
**STEP 1 =>** Download all the files from Kaggle    
**STEP 2 =>** Upload to GitHub account

**STEP 3 =>** Creating Azure resources in MS Azure   
**Resources created - **   
a. Resource Group   
b. Storage Account  
c. Containers - Bronze & Silver  
d. Azure Data Factory workspace  
e. Databricks workspace  
f. Microsoft Entra Id  

**STEP 4 =>** Launch ADF workspace to ingest raw data from Github to ADLS (**BRONZE container**)
<img width="614" height="302" alt="image" src="https://github.com/user-attachments/assets/2ee7a429-a7eb-40fa-ba27-86201b37984d" />

**STEP 5 =>** Create Microsoft Entra Id

**STEP 6 =>** Launch Databricks Workspace 
a. Create compute
b. Create a folder in the Databricks workspace
c. Run the given code (Project Documentation) to access data in the data lake
d. Read the data from all folders/csv file
e. Perform transformations as per requirement
f. Write the data to MS Azure (**SILVER container**)

**STEP 7 =>** Create views from the silver data (**GOLD layer**)

