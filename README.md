# E-Commerce (Admin) with React, Node, Express, Sequelize, MySQL

## Structure
- server/server.js: synchronize all models
- server/app/config: configure database connection 
- server/app/models: instantiate the database connection and create object to table mapping (models)
- server/app/controllers: execuete CRUD queries
- server/app/routes: match requests and send responses

- client/src/components: 3 components for creating, reading, updating, and deleting products

## Setup
- Running the backend server:  ```node server.js```
- Running the client: ```npm start```

## Summary
### Products Page
- Display a list of products available
- Select an existing product in the system to display its details
- Search for a product by its title, rating, or price

### Add Product Page
- Add a product to the system by providing the details of the product (title, category, price, color, rating, image) 

### Edit Product Page
- Update product information 
- Delete an existing product
