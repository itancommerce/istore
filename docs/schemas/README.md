# Database Schemas

All database schemas should placed in this folder.
Use JSON to descibe each schema and To identify the Mongodb type for each field please specify the value of each key. 
Write in the value of each key if you need to write further details.

example: 

Users' Schema
```
{
    "_id" : "ObjectId",
    "name" : "String",
    "age" : "Int32",
    "status" : "Int32, enum ACTIVE | DEACTIVE | SUSPEND"
}
```