# mysql_cloudmanaged_databases

## Setup MySQL on GCP
1. After signing in, create a new project, and name the project. The name I have chosen is **eugene-wk4a-assignment**
2. Keep orgnaization as StonyBrook, and select the location as AHI-GCP
3. On the left hand sign with the navigation menu, click on SQL
4. CLick: Create Instance, MySQL, Enable API
5. Create your instance name and passwordMac
6. Make sure that; database version: 8.0, SQL edition: Enterprise, Preset: Sandbox, Machine config: Shared core; 1 vCPU, 0.614 GB, Connection: public IP, Network: Allow All and 0.0.0.0/0
7. Create
8. Follow [guide](https://mycourses.stonybrook.edu/d2l/le/content/695780/viewContent/27020091/View) for MySQL Workbench for Database Interaction 


## Setup MySQL on Azure
1. Log in Azure, search: Azure Databases for MySQL, press create
2. Make sure; Flexible server, Azure for students, create a resource group name, and server name
3. Make Compute + Storage: Burstable B1ms 1 vCores 2 GiB RAM, 20 GiB storage, Auto Scale IOPS, Georeduncency: Disabled
4. Create admin user name, password
5. Click Next: Networking
6. Make sure; connectivity: public Access and private endpoint, Firewall rules: Allow public access from any Azure service within Azure to this server, 0.0.0.0 - 255.255.255.255
7. Create
8. Follow [guide](https://learn.microsoft.com/en-us/azure/mysql/flexible-server/connect-workbench) for MySQL Workbench for Database Interaction
