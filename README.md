# Inventory Management System MERN Stack App

This guide will help you set up and run an Inventory Management System built with the MERN stack (MongoDB, Express.js, React, and Node.js). The application allows you to perform CRUD (Create, Read, Update, Delete) operations on product data stored in a MongoDB database.

## Prerequisites
- **Node.js**: Ensure you have Node.js installed. You can download it from [Node.js Official Website](https://nodejs.org/).
- **MongoDB**: Install MongoDB and MongoDB Compass for database management. You can download MongoDB from [MongoDB Official Website](https://www.mongodb.com/try/download/community) and MongoDB Compass from [MongoDB Compass](https://www.mongodb.com/products/compass).

## Installation and Setup

### 1. Clone the Repository
First, clone the repository to your local machine using Git. If you don’t have Git installed, you can download and install it from [Git Official Website](https://git-scm.com/).

```bash
git clone https://github.com/your-repository-url/inventory-management-system-mern
cd inventory-management-system-mern
```

### 2. Install Dependencies
Navigate to the project directory in VS Code or any other code editor.

Run the following command in the terminal to install the necessary Node.js dependencies:

```bash
npm install
```

### 3. Set Up MongoDB Database
Open MongoDB Compass and perform the following steps:

1. **Create Database**: Name the database `IMS`.
2. **Create Collection**: Within the `IMS` database, create a collection named `products`.

This is how it should look in MongoDB Compass:
![MongoDB Compass](https://github.com/mhy20401/Inventory-Management-System-MERN-CRUD-Project/assets/99351091/86ed0828-84b8-43b0-89fd-8caa17b88833)

### 4. Run the Application
Open two terminals in VS Code (split them for convenience):

#### Terminal 1: Backend Server

Navigate to the `Backend` directory and start the server:

```bash
cd Backend
npm run server
```

This will start the backend server and connect to the MongoDB database.

#### Terminal 2: Frontend Client

Navigate to the frontend directory and start the React application:

```bash
cd Frontend
cd inventory_management_system
npm start
```

This will start the React development server, and the application should open automatically in your default web browser.

![Starting Frontend](https://github.com/mhy20401/Inventory-Management-System-MERN-CRUD-Project/assets/99351091/93fa528b-bc88-49c2-9922-19b317336b7c)

## Application Usage

Once the application is running, you can perform the following operations:

### 1. Display Products (GET)

View all products in the database. The products are fetched from the `products` collection in MongoDB.

![GET Products](https://github.com/mhy20401/Inventory-Management-System-MERN-CRUD-Project/assets/99351091/09f7d43a-344b-4122-b415-b3736307cf45)

### 2. Add a New Product (POST)

Insert a new product into the `products` collection. Fill out the form with the necessary product details and submit.

![POST New Product](https://github.com/mhy20401/Inventory-Management-System-MERN-CRUD-Project/assets/99351091/d31e9f36-c119-4a04-9cc0-ddc9fe94b159)

![POST New Product](https://github.com/mhy20401/Inventory-Management-System-MERN-CRUD-Project/assets/99351091/39ec387f-5efc-4c1f-a7eb-a87612acc17a)

![POST New Product](https://github.com/mhy20401/Inventory-Management-System-MERN-CRUD-Project/assets/99351091/a6b5c6bf-77d7-41ab-9ca0-3a8bfc71954d)

![POST New Product](https://github.com/mhy20401/Inventory-Management-System-MERN-CRUD-Project/assets/99351091/3d43e877-c2e6-414b-bef9-410caae1668e)

### 3. Update a Product (PUT)

Select a product and update its details. Submit the changes to modify the existing product in the database.

![PUT Update Product](https://github.com/mhy20401/Inventory-Management-System-MERN-CRUD-Project/assets/99351091/d35f7ab0-3fda-4b1c-9055-67ca8c7b2ab6)

![PUT Update Product](https://github.com/mhy20401/Inventory-Management-System-MERN-CRUD-Project/assets/99351091/7dd107db-6fde-416d-b5c6-2175916f872f)

### 4. Delete a Product (DELETE)

Remove a product from the database. This action is irreversible and will permanently delete the product from the `products` collection.

![DELETE Product](https://github.com/mhy20401/Inventory-Management-System-MERN-CRUD-Project/assets/99351091/d846ff43-6abd-4baa-9ed6-df736f2d411e)

![DELETE Product](https://github.com/mhy20401/Inventory-Management-System-MERN-CRUD-Project/assets/99351091/cc6368bd-f391-4d6b-b814-c931d48a0878)

## Summary

This Inventory Management System allows you to seamlessly manage product data using a full stack MERN application. It demonstrates the power of MongoDB for data storage, Express.js for backend routing, React for a dynamic frontend, and Node.js for running the server.

Feel free to modify and enhance this project to suit your needs. Happy coding!

---

**Note:** For detailed setup instructions or troubleshooting, refer to the project's GitHub repository or documentation.

---

If you have any questions or run into issues, don't hesitate to ask for further assistance.