# E-Commerce Back End

Tracking information of your products can be tricky in an ever growing company and technological world. This simple application can help your business keep track of your products, what categories they are in, and any tags associated with them! Keep organized!

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
## Description
When starting up and using your back-end application for your business, it is important to follow these simple steps. 

### Step 1: Seed Your Database

 ![Seeding The Database](./Develop/Assets/E-Commerce-Back-End-SeedingDB.gif)

 1. Create your database using a schema on the MySQL Workbench application. A schema has been provided for you under the db folder. 
 2. Using the command terminal, type "npm run seed" to create dummy information to populate your database as a start. 
 3. Check to make sure your database has been properly seeded with the dummy information.

 ### Step 2: Start Your Server / Categories API Routes
 ![Categories API Route](./Develop/Assets/E-Commerce-Back-End-Categories-API-Routes.gif)

 1. Start your server by writing "node server" in your terminal. Be sure you are in the proper folder for running this command. 
 2. When the command line is running, the terminal will inform you that the server is now listening for any changes to your database you wish to submit. 
 3. There are five API routes for Categories: Get (all and individual), Post, Put, and Delete. 
 4. GET will retrieve all your Categories and all associated products listed for that Category in your database. If you want a single Category, you can call for its unique ID number as seen in the GIF above. 
 5. POST will allow you to add a new Category to your database. 
 6. PUT will allow you to edit a Category's information in the database. Call for its unique ID, then submit your changes as seen in the GIF above. 
 7. DELETE will allow you to remove a Category from your database and all Products associated with that Category. Call for its unique ID number, and the application will remove the Category. 

### Step 3: Products API Routes
![Products API Route](./Develop/Assets/E-Commerce-Back-End-SeedingDB.gif)
1. There are five API routes for Products: Get (all and individual), Post, Put, and Delete. 
2. GET will retrieve all your Products and all associated Tags and Categories listed for that Product in your database. If you want a single Product, you can call for its unique ID number as seen in the GIF above.
3. POST will allow you to add a new Product, its Category ID, its price, and its stock and its associated Tag IDs to your database. 
4. PUT will allow you to edit a Products' information in the database. Call for its unique ID, then submit your changes as seen in the GIF above.
5. DELETE will allow you to remove a Product from your database. Call for its unique ID number, and the application will remove the Product.

### Step 4: Tags API Routes
![Tags API Route](./Develop/Assets/E-Commerce-Back-End-Tags-API-Routes.gif)
1. There are five API routes for Products: Get (all and individual), Post, Put, and Delete.
2. GET will retrieve all your Tags and all associated Products listed for that Tag in your database. If you want a single Tag, you can call for its unique ID number as seen in the GIF above.
3. POST will allow you to add a new Tag to your database. 
4. PUT will allow you to edit a Tag's information in the database. Call for its unique ID, then submit your changes as seen in the GIF above.
5. DELETE will allow you to remove a Tag from your database. Call for its unique ID number, and the application will remove the Tag.

## Features
- Users can create a database for their application and seed with through the terminal with set-up information.
- Users can start up a server through the terminal. 
- Users can GET, POST, PUT, and DELETE Categories, Products, and Tags. 



