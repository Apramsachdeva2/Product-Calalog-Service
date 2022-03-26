# Product-Calalog-Service
A REST API that provides endpoints for clients to add, delete and retrieve products from productsDB

This API is built using spring boot, RestController annotation, springJDBC.

MySQL is used for database.

url:- https://apram-prod-service.herokuapp.com/productservice/products

Send a get request to retrieve all the products present in productsDB.

Sends response status 'NOT_FOUND' in case of any Exception.
