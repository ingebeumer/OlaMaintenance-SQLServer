# Description
Power BI report on the CommandLog table by Ola Hallengren's SQL Server Maintenance Solution (all credits for the solution itself to https://ola.hallengren.com/). The report provides visualized insights on the CommandLog table in a SQL Server instance to support you in managing your database maintenance: planning, duration, what maintenance is done. All in the report is based on the CommandLog table.
 
Custom reporting built on the output of the Ola Hallengren Maintenance Solution in the CommandLog table. 
- Data is available when commands of this maintenance solution are executed with @LogToTable = 'Y'. 
- This report is built to visualize data of a specific SQL Server instance. 
 
> Please note this report is only aware of databases and objects that have received maintenance through the Ola Hallengren Maintenance Solution, it cannot provide full insights on your databases and their objects, nor will it have insights in activity through other jobs and processes.
 
# Data source
The report is based on following data sources.

- CommandLog table.
 
# Requirements
Get Power BI desktop either by installing as an app from the Microsoft Store or downloading directly.

- https://aka.ms/pbidesktop (Microsoft Store)
- https://learn.microsoft.com/en-us/power-bi/fundamentals/desktop-get-the-desktop
 
# Edit parameters 
Edit parameters SQL Server instance and database to connect to the database with the CommandLog table you want to analyze.
### Edit parameters on opening the Power BI template file (pbit) and Load the data
![image](https://user-images.githubusercontent.com/40343254/171740150-f61c1986-3588-4ea1-8485-9c589d31bb77.png)

### Edit parameters in a Power BI report file (pbix)
![image](https://user-images.githubusercontent.com/40343254/171739479-b0a04658-b247-4d95-a67f-5c32dd4df0e2.png)

# Refresh data
Open the pbix file with Power BI desktop. Get the latest data by refreshing all visuals in this report through Home + Refresh.

![Refresh Power BI desktop file](https://user-images.githubusercontent.com/40343254/168686666-e15ca265-430f-463a-a31c-e5dc4953ee3f.png)
