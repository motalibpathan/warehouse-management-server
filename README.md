# Car Max server

## Server Link: [https://enigmatic-harbor-04768.herokuapp.com/](https://enigmatic-harbor-04768.herokuapp.com/)

## Client Live site link [https://warehouse-management-85499.web.app/](https://warehouse-management-85499.web.app/)

<p>
This is server for Car Max website. Here some API's are inventory, inventory by id, filter inventory by email, update inventory quantity, delete inventory and Insert an inventory routes and generate jwt token when login and verify given token from client side.
</p>

## Features and Functionalities

- inventory route for get inventory, if with query 'size' then number of inventory will send by 'size'
- inventoryByEmail routes filter the inventories by query parameters 'email' also verify client given token after verify it will be send inventories data
- Also has delete inventory route it receive a dynamic parameter 'id' and delete particular inventory
- Post inventory will be insert a inventory to the database
- Patch inventory will update quantity and sold information
- Login route api will generate a jwt token and sent it to client.

## Technologies used

- Node js
- Express js
- Mongodb
- jsonwebtoken
- dotenv
- cors
