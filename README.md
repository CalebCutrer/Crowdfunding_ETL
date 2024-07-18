# Crowdfunding_ETL
Project-2

### Importing & Formatting Data: 
1. The necessary data can be found in the "Resources" folder within the repository, with the raw input data consisting of two Excel files: "crowdfunding.xlsx" and "contacts.xlsx." 
2. To get the data into the proper format, execute the code found in the "ETL_Mini_Project_CCutrer_MJudy" Jupyter notebook file. Upon running the code, the .xlsx files will be used to create four .csv files: "campaign.csv", "category.csv", "subcategory.csv", and "contacts.csv". The newly created .csv files will be stored in the "Resources" folder that houses the input data.
3. With the data files now created, the database can be constructed.

### Database Management: 
1. To create the database, please open PgAdmin and then open the database server.
2. Create new database titled "crowdfunding_db"
3. Select the "Query Tool" from the table section (right click on the table section).
4. Open the "crowdfunding_db_schema.sql", the provided ERD, and run the script create a table schema for the four CSV files.
5. To import the data, right click on a table and select Import/Export Data. When importing table content to the database, import the .csv files in this order: category, contacts, subcategoy, and then campaign.
