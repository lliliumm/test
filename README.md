[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-f059dc9a6f8d3a56e377f745f24479a46679e63a5d9fe6f495e02850cd0d8118.svg)](https://classroom.github.com/online_ide?assignment_repo_id=5921610&assignment_repo_type=AssignmentRepo)
# Cloud Engineer Case Study
## Description
This is a sample Node.js Restful CRUD API which uses Express as web framework and MySQL as database.
### Required Components
* Node.js v14
* MySQL 8
## Project setup
### Install necessary modules
```
npm install
```
### Database Config
* Run the script [db.sql](https://github.com/sinag/Cloud_Engineer_Case_Study/blob/master/app/config/db.sql) on MySQL to create database and table.
* Edit database configuration script [db.config.js](https://github.com/sinag/Cloud_Engineer_Case_Study/blob/master/app/config/db.config.js) file.
## Run
### Start express application
```
node server.js
```
Open your browser, enter the url http://localhost:3000/
### Test
| Method  | Url | Action |
| ------- | --- | ------ |
| GET | /customers | get all Customers |
| GET | /customers/42 |	get Customer with id=1 |
| POST | /customers |	add new Customer |
| PUT | /customers/42 |	update Customer with id=1 |
| DELETE | /customers/42 | remove Customer with id=1 |
| DELETE | /customers | remove all Customers |
