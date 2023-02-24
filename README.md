# All City And State Of Turkey's SQL Queries and Table Structures

##Country Table
id : Guid (unique)
created : Date (nullable)
created_by : Date (nullable)
last_modified : Date (nullable)
last_modified_by : varchar (nullable)
status : tinyint 
deleted : tinyint (nullable for soft delete purposes)
name : varchar (unique)

##City Table
id : Guid (unique)
created : Date (nullable)
created_by : Date (nullable)
last_modified : Date (nullable)
last_modified_by : varchar (nullable)
status : tinyint 
deleted : tinyint (nullable for soft delete purposes)
name : varchar (unique)
country_id : Guid (reference table country)

##State Table
id : Guid (unique)
created : Date (nullable)
created_by : Date (nullable)
last_modified : Date (nullable)
last_modified_by : varchar (nullable)
status : tinyint 
deleted : tinyint (nullable for soft delete purposes)
name : varchar (unique)
city_id : Guid (reference table city)




