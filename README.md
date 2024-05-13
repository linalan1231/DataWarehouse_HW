**Data Warehouse Homework #1 and hw#2**


Data Descriptions:
The data came from the NYC OpenData containing information on NYC air quality survilance data base on different neighborhood. The Air quality Data itself contains 18026 rows and  12 columns like UniqueID, IndicatorID, Name, Measure, Measure Info, Geo Type Name, Geo Join ID, Geo Place Name, Time Period, Start Date, Value, as well as Data Value. To view the data dictionary or to get the data source, please click on the link below. 

Link to data source:
https://catalog.data.gov/dataset/air-quality

Data Dictionary:
https://data.cityofnewyork.us/Environment/Air-Quality/c3uy-2p5r/about_data or 

Updated Data Dictionary
<img width="515" alt="Screenshot 2024-05-13 at 5 56 51 PM" src="https://github.com/linalan1231/DataWarehouse_HW/assets/70352593/adf5b597-f3f9-412d-a6fc-da317cc9277b">


Part 1 Data modeling: 
To examine and understand the today, the first step was to read and understand the process behind the data. Then the data were divided into two categories: Quanlitative vs Quantitative. After 
dividing the dataset into two categories, fact and dimension tables were created to perform dimensional modeling. The attachment below shows the separation between fact and dimension table.
<img width="1180" alt="Screenshot 2024-04-25 at 10 45 17 AM" src="https://github.com/linalan1231/DataWarehouse_HW/assets/70352593/9141e4a2-3628-45c9-8525-eee095c083ce">

The next step was to use DB schema to create the physical and logical model and lastly uploaded to a container to be stored in the cloud. 
<img width="772" alt="Screenshot 2024-04-25 at 10 55 49 AM" src="https://github.com/linalan1231/DataWarehouse_HW/assets/70352593/3966ebbc-e9ce-4ece-ab72-3147c92243ae">

Part2
Data then were transform base on the dimesional model using python scripts. Then it was loaded into Microsoft Azure Postgres Flexible Server for data visualization and anlysis.

Data Visualization
Link: https://cuny907-my.sharepoint.com/:u:/r/personal/alan_lin37_login_cuny_edu/Documents/Attachments/CIS9440HW.pbix?csf=1&web=1&e=SDLCdf

Findings: 

Average Data Value By year
<img width="1027" alt="Screenshot 2024-05-13 at 5 37 24 PM" src="https://github.com/linalan1231/DataWarehouse_HW/assets/70352593/157aeaa5-1150-44e0-8133-c9e74ce25508">

Sum of Data Value By Year
<img width="1066" alt="Screenshot 2024-05-13 at 5 37 54 PM" src="https://github.com/linalan1231/DataWarehouse_HW/assets/70352593/fd222374-3dd1-4580-b665-481e25a8a4ee">

Average of Data Value by Borough
<img width="936" alt="Screenshot 2024-05-13 at 5 38 06 PM" src="https://github.com/linalan1231/DataWarehouse_HW/assets/70352593/daf87390-71f3-4761-8e86-4a740242a904">

Median Data Value Heat Map
<img width="1024" alt="Screenshot 2024-05-13 at 5 38 45 PM" src="https://github.com/linalan1231/DataWarehouse_HW/assets/70352593/054f2a55-f27f-4766-9458-fefcf7fc7fb5">
