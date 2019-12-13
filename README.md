## Starter project RESTFUL API with : Express - Node.js - React - MySQL 

# Rescept the architecture
- Models/Controllers/Routes
- GET, POST, PUT, DELETE : A walkthrough with JavaScript’s Fetch API

### Step 1
 Clone the repo
 Check if node-module is corecctly installed
 
### Step 2 
  Create the DB. 
   1) mysql -u root -p
   2) compile the file 'starter/back-app/stores/clients.sql'
 
### Step 3
  Create file 'db.config.js' in folder 'starter/back-app'
  ```
    module.exports = {
      HOST :  'localhost', 
      USER :  'root', 
      PASSWORD :  YOUR PASSWORD,
      DB :  'game'
    }
```

### Step 4
 1) In 'front-app' : ```npm start```
 2) In 'back-app' : ``` node server.js```


 
