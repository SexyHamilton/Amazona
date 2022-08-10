# Amazona

1. Initial Steps:

   1. Install tools
   2. Create React app
   3. Create git repository

2. List Products:

   1. Create products array
   2. Add product images
   3. Render products
   4. Style products

3. Add Routing

   1. npm i react-router-dom
   2. create route for home screen
   3. create router for product screen

4. Create Node.js Server

   1. run npm init in root folder
   2. update package.json set type: module
   3. add .js to imports
   4. npm install express
   5. create server.js
   6. add start command as node backend/server.js
   7. require express
   8. create route for / return backend is ready
   9. move products.js from frontend to backend
   10. create route for /api/products
   11. return products
   12. run npm start

5. Fetch Products From Backend

   1. set proxy in package.json
   2. npm install axios
   3. use state hook
   4. use effect hook
   5. use reducer hook

6. Manage state with reducer hook:

   1. define reducer
   2. update fetch data
   3. get state from useReducer

7. Add bootstrap UI Framework

   1. npm install react-bootstrap bootstrap
   2. update App.js

8. Create Product and Rating Component

   1. create Rating component
   2. Create Product component
   3. Use Rating component in Product component

9. Create Product Details Screen

   1. fetch product from backend
   2. create 3 columns for image, info and action

10. Create Loading and Message Component

    1. create loading component
    2. use spinner component
    3. create message component
    4. create utils.js to define getError function

11. Implement Add to Cart

    1. create React Context
    2. define reducer
    3. create store provider
    4. implement add to cart button click handler

12. Complete Add To Cart

    1. check exist item in the cart
    2. check count in stock in backend

13. Create Cart Screen

    1. create 2 columns
    2. display items list
    3. create action column

14. Complete Cart Screen

    1. click handler for inc/dec item
    2. click handler for remove item
    3. click handler for checkout

15. Create Signin Screen

    1. create signin form
    2. add email and password
    3. add signin button

16. Connect To MongoDB Database

    1. create atlas mongodb database
    2. install local mongodb database
    3. npm install mongoose
    4. connect to mongodb database

17. Seed Sample Data

    1. create product model
    2. create user model
    3. create seed route
    4. use route in server.js
    5. seed sample product

18. Complete Signin Screen

    1. handle submit action
    2. save token in store and local storage
    3. show user name in header

19. Create Shipping Screen

    1. create form inputs
    2. handle save shipping address
    3. add checkout wizard bar

20. Create Sign Up Screen

    1. create input forms
    2. handle submit
    3. create backend api

21. Implement Select Payment Method Screen

    1. create input forms
    2. handle submit

22. Create Place Order Screen

    1. show cart items, payment and address
    2. handle place order action
    3. create order create api

23. Implement Place Order Action

    1. handle place order action
    2. create order api

24. Create Order Screen

    1. create backend api for order:/id
    2. fetch order api in frontend
    3. show order infomation in 2 columns

25. Pay Order By Paypal

    1. generate paypal client id
    2. create api to return client id
    3. install react-paypal-js
    4. use paypalScriptProvider in index.js
    5. use usePaypalScriptReducer in Order Screen
    6. implement payloadScript function
    7. render paypal button
    8. implement onApprove payment function
    9. create pay order api in backend

26. Display Order Histoty

    1. create order screen
    2. creatr order history api
    3. use api in the frontend

27. Create Profile Screen

    1. get user info from context
    2. show user information
    3. create user update api
    4. update user info

28. Publish To Heroku
    1. create and config node project
    2. serve build folder in frontend folder
    3. create heroku account
    4. connect it to github
    5. create mongodb atlas database
    6. set database connection in heroku env variables
    7. commit and push
