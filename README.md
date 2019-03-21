# RestFull-API-for-e-commerce
Restful API for e-commerce app based on node js and data saved in mongoDB by Shojib97

CRUD

////////////////////////////////////////////////////////
///////////////////////ACCOUNTS//////////////////////////
////////////////////////////////////////////////////////

#CREATE
POST: http://localhost:8000/account/signup

{
 "username": "",
 "email": "",
 "password": ""
}

#LOGIN
POST: http://localhost:8000/account/signin

{
 "email": "",
 "password": ""
}

#READ
GET: http://localhost:8000/account

#UPDATE
PUT: http://localhost:8000/account/updateUser

{
 "id": "",
 "username": "",
 "email": "",
 "password": ""
}

#DELETE
DELETE: http://localhost:8000/account/deleteUser

{
 "id": ""
}


////////////////////////////////////////////////////////
////////////////////////ORDERS//////////////////////////
////////////////////////////////////////////////////////

#CREATE
POST: http://localhost:8000/order/addOrder

{
 "firstName": "",
 "lastName": "",
 "addressLine1": ""
 "addressLine2": "",
 "city": "",
 "postcode": "",
 "contry": ""
}

#READ
GET: http://localhost:8000/order/getOrder

#UPDATE
PUT: http://localhost:8000/order/updateOrder

{
 "id": "",
 "firstName": "",
 "lastName": "",
 "addressLine1": ""
 "addressLine2": "",
 "city": "",
 "postcode": "",
 "contry": ""
}

#DELETE
DELETE: http://localhost:8000/order/deleteOrder

{
 "id": ""
}


////////////////////////////////////////////////////////
////////////////////////PAYMENTS////////////////////////
////////////////////////////////////////////////////////

#CREATE
POST: http://localhost:8000/payment/savepayment

{
 "creditCardNumber": "",
 "expire": "",
 "CVVCode": ""
}

#READ
GET: http://localhost:8000/payment/getPayment

#UPDATE
PUT: http://localhost:8000/order/updatePayment

{
 "id": ""
 "creditCardNumber": "",
 "expire": "",
 "CVVCode": ""
}

#DELETE
DELETE: http://localhost:8000/order/deletePayment

{
 "id": ""
}

////////////////////////////////////////////////////////
////////////////////////PRODUCTS////////////////////////
////////////////////////////////////////////////////////

#CREATE
POST: http://localhost:8000/products/createProducts

{
 "imageUrl": "",
 "name": "",
 "price": "",
 "category": "",
 "size": ""
}

#READ
GET: http://localhost:8000/products

PUT: http://localhost:8000/products/createProducts

{
 "imageUrl": "",
 "name": "",
 "price": "",
 "category": "",
 "size": ""
}










