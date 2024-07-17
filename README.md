# 🛒E-Commerce Backend
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

---

## Description
##### ✨E-Commerce Backend: Powering Your Online Store✨

E-Commerce Backend is a robust API built with Express.js and Sequelize to interact with a PostgreSQL database. This application provides a comprehensive backend for an e-commerce website, enabling CRUD operations for products, categories, and tags. It is designed to help internet retail companies manage their product inventory efficiently.

*Student Assignment for U of U Bootcamp* 

---

## Table of Contents
- [Application](#application)
- [Video](#video)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [License](#license)
- [Credits](#credits)
- 

---

## Application

This application is designed to be run locally for development and testing purposes.

&nbsp;

---

## Video

#Video showing functionality on the deployed page

-(Click here to wath)[https://watch.screencastify.com/v/wGA0PEKnLXuZugPtNzaT]

&nbsp;


---

## Installation

To use this E-Commerce Backend application, you'll need to have [Node.js](https://nodejs.org/en/download/package-manager) and [PostgreSQL](https://www.postgresql.org/download/) installed on your machine. If you don't need set-up help, move on to [Usage](#usage) for functionality. 

Follow these steps to set up the project:

1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/your-username/ecommerce-backend.git
&nbsp;

2. **Now -- in your terminal, navigate to your Project Directory**
    ```bash
    cd ecommerce-backend
&nbsp;

3. **Install Required Dependencies**
    ```bash
    npm install
&nbsp;

4. **Create a `.env` file in the root of your project and add the following:**
    ```bash
    DB_NAME='ecommerce_db'
    DB_USER='your_postgres_username'
    DB_PASSWORD='your_postgres_password'
&nbsp;

5. **Create the Database Schema:**
    - Ensure PostgreSQL is running.
    - Run the following command to create the database and tables: 
    ```bash
    psql -U postgres -d ecommerce_db -f "path/to/schema.sql"
&nbsp;

6. **Seed the Database:**
    ```bash
    npm run seed
&nbsp;

7. **Start the Server:**
    ```bash
    npm start
&nbsp;

---

## Usage
Follow these steps to use the E-Commerce Backend application:

1. **Start the Application:**
&nbsp;
   
   - Makes sure you're in the right directory. Then, run the following command in your terminal:
   ```bash
   npm start
&nbsp;

2. **Test the API Endpoints**
- Use a tool like Insomnia or Postman to interact with the API. I personally use [Insomnia](https://insomnia.rest/download)
- The server should be running at http://localhost:3001.
&nbsp;
---

## API Endpoints
*JSON for specific routes can be seen in the video walkthrough*

### Categories 

 - GET /api/categories
    --Retrieves all categories.
 - GET /api/categories/1
    -- Retrieves a single category by ID.
 - POST /api/categories
   -- Creates a new category.
 - PUT /api/categories/
   -- Updates a category by ID.
 - DELETE/api/categories/
   -- Deletes a category by ID.

### Products 

 - GET /api/products
   -- Retrieves all products.
 - GET /api/products/
   -- Retrieves a single product by ID.
 - POST /api/products
   -- Creates a new product.
 - PUT /api/products/
   -- Updates a product by ID.
 - DELETE /api/products/
   -- Deletes a product by ID.


### Tags 

 - GET /api/tags
    --Retrieves all tags.
 - GET /api/tags/
    -- Retrieves a single tag by ID.
 - POST /api/tags
   -- Creates a new tag.
 - PUT /api/tags/
   -- Updates a tags by ID.
 - DELETE/api/tags/
   -- Deletes a tag by ID.


---

## License
This project is licensed under the MIT license.

---


## Credits
- Developer: &nbsp; me 💁🏼‍♀️
&nbsp;
- [Starter code](https://github.com/coding-boot-camp/bookish-sniffle)
- [Node.js](https://nodejs.org/en/download/package-manager)
- [Express.js](https://expressjs.com/)
- [Sequelize](https://sequelize.org/)
- [PostgreSQL](https://www.postgresql.org/)


## Notes
Make sure to replace placeholders like "your-username" and "your_postgres_username" with your actual GitHub username and PostgreSQL username, respectively. Additionally, update the paths as necessary to reflect your project's structure.








