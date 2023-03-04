Route in this server:
POST    http://localhost:3000/api/login : Using Postman, set body with the following:
{
    "username": "admin",
    "password" : "MindX@2022"
}
to get a token.

GET    http://localhost:3000/api/inventories/all : Pass the token in the body to access to inventories

GEt    http://localhost:3000/api/orders?item=pecans: Pass the token in body and value for item query to get orders based on value

GET    http://localhost:3000/api/inventories/low: Pass the token in body to get inventories with quantity below 100