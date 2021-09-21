# Flask
Flask application for review


CRUD implementation using POSTMAN

{
  "database": "Employees",
  "collection": "Emp"
}

 it consists of 2 fields — First_Name and Age. We are going to see how we can use these 2 fields to add or delete more data.
 
 {
  "database": "Employees",
  "collection": "EMp",
  "Document": {
    "First_Name": "Apurv",
    "Age": 23
  }
}

As we can see the new document got successfully inserted in ‘Emp’ collection.

{
  "database": "Employees",
  "collection": "Emp",
  "Filter": {
    "first_name": "Apurv"
  },
  "DataToBeUpdated": {
    "Last_Name": "John Doe",
    "Age": 25
  }
}
As we can see the new document got successfully Updated in ‘Emp’ collection.

{
  "database": "Employee",
  "collection": "Emp",
  "Filter": {
    "First_Name": "Apurv"
  }
}
As we can see the new document got successfully Deleted in ‘Emp’ collection.
