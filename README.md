# Inventory Project

This application is a basic archive system. It will allow you to create an inventory of household items. These items can be anything that you would like cataloged in your household(eg: items, cleaning supplies, clothing).

I will be using several new technologies including the Python back-end and the React front-end.


### Technologies:

* Back-End:
  * Python
  * pyodbc
  * MSSQL

* Middleware:
  * Python
  * Flask

* Front-End:
  * JavaScript
  * React
  * Bootstrap

### To do:
##### IN PROGRESS: Connect React to Python endpoints / import bootstrap


- [ ] Back-end
  - [x] Connect API to DB
  - [ ] Create CRUD Queries
    - [x] Create Create Queries
    - [x] Create Read Queries
    - [ ] Create Update Queries
    - [x] Create Delete Queries
  - [ ] Create any additional Queries
  - [ ] Document ALL Queries

- [ ] Middleware: 
  - [x] Initialize python api
  - [ ] Create CRUD endpoints
    - [x] Create Create endpoints
    - [x] Create Read endpoints
    - [ ] Create Update endpoints
    - [x] Create Delete endpoints
  - [ ] Create any additional endpoints
  - [ ] Document ALL endpoints
  - [ ] Implement Contact model see <a href='https://kite.com/python/docs/flask.jsonify'>this.</a>
    - [x] Create Model
    - [x] Import Model
    - [ ] Optimize code to implement model 
      - [ ] Learn how to jsonify custom class
   
- [ ] Front-end:
  - [x] Initialize React app using <a href="https://github.com/facebookincubator/create-react-app#create-react-app--">create-react-app</a>
  - [x] Add <a href="https://create-react-app.dev/docs/adding-bootstrap/">Bootstrap</a> for styles
  - [ ] Consume RESTful Python API
 

### User Stories:

- [ ] As a User, I want to be able to see a list of items - /GET/ALL items
- [ ] As a User, I want to be able to create a item to add to my collection - /POST/item
- [ ] As a User, I want to be able to delete a item from my collection - /POST/item
- [ ] As a User, I want to be able to edit a item in my collection - /PUT/item

### Bonus:
- [ ] As a User, I want to be able to select from a list of collections to edit (administrator functions)
- [ ] As a User, I want to be able to see a list of all items in the collection
- [ ] As a User, I want to be able to create an item to add to the collection
- [ ] As a User, I want to be able to delete an item from the collection
- [ ] As a User, I want to be able to edit an item in the collection


Helpful links:
* <a href="https://dash.plotly.com/react-for-python-developers">React/Python</a>
* <a href="https://developer.okta.com/blog/2018/12/20/crud-app-with-python-flask-react">CRUD-Python-Flask</a>

<!-- testing git on linux -->
