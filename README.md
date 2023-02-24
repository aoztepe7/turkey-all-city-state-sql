# All City And State Of Turkey's SQL Queries and Table Structures

##Country Table <br/>
id : Guid (unique) <br/>
created : Date (nullable) <br/>
created_by : Date (nullable) <br/>
last_modified : Date (nullable) <br/>
last_modified_by : varchar (nullable) <br/>
status : tinyint  <br/>
deleted : tinyint (nullable for soft delete purposes) <br/>
name : varchar (unique) <br/>

##City Table <br/>
id : Guid (unique) <br/>
created : Date (nullable) <br/>
created_by : Date (nullable) <br/>
last_modified : Date (nullable) <br/>
last_modified_by : varchar (nullable) <br/>
status : tinyint  <br/> 
deleted : tinyint (nullable for soft delete purposes) <br/>
name : varchar (unique) <br/>
country_id : Guid (reference table country) <br/>

##State Table <br/>
id : Guid (unique) <br/>
created : Date (nullable) <br/>
created_by : Date (nullable) <br/>
last_modified : Date (nullable) <br/>
last_modified_by : varchar (nullable) <br/>
status : tinyint  <br/>
deleted : tinyint (nullable for soft delete purposes) <br/>
name : varchar (unique) <br/>
city_id : Guid (reference table city) <br/>




