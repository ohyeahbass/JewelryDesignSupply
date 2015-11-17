##Jewelry Design Supply

Jewelry Design Supply is an ecommerce site. 

##General Info
* It was built using local storage for a shopping cart.
* Login saves customer info and uses Passport for auth. 
* Admin page that allows to easily enter new products as well as update and delete. 
* Admin also allows to check current orders and save to fulfilled.

##MEAN STACK
  1. FrontEnd- Angular
    * Angular is a front end MVC framework.  Used to create front end web application as well getting data with $http, moving       that data around and providing functionality to the html.
  2. BackEnd - Node Express MongoDb 
    * Node was used for my web server.
    * Express was used to make building the web server easy.
    * MongoDb was used as the data base. There are four collections:user, products,orders to be processed, processed orders.
    

 

##Shopping Cart
* Local storage saves current items to users computer.
* Uses Stipe to complete payments.



|Dependencies     |Used For|
|-------------------|-------------------------------------------|
|bcryptjs           |This makes turns the password to a hash.|
|body-parser        |Body parser is used as middleware that returns objects in req.body or returns an error to the callbacks|
|cors               |Allows for http requests from different domain than the one that served the request.|
|express-session    |Used to save the user info to the session in server once logged in.|
|mongoose           |Used to help model my schema's.|
|passport           |Passport was used to authenticate users in Nodejs|
