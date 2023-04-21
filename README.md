

# PH&Co Stock Check Web App

This is a web application built with React, Node.js, MongoDB, Mongoose, and Express. It is designed to be used by LAI CHEE HOONG for stock check purposes on both PCs and smartphones.

## Features

The PH&Co Stock Check Web App provides the following features:

- User authentication: users can create an account and log in to the app.
- Stock check: users can check the stock of products.
- Admin panel: admins can manage users and products.

## Prerequisites

Before running the app, make sure you have the following software installed on your system:

- Node.js
- MongoDB

## Installation

To install the app, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the root directory of the app.
3. Run `npm install` to install the dependencies.
4. Create a `.env` file with the following content:

```
MONGODB_URI=<your MongoDB connection string>
JWT_SECRET=<your JWT secret>
```

Replace `<your MongoDB connection string>` with the connection string to your MongoDB instance, and `<your JWT secret>` with a secret string used for JWT token encryption.

5. Run `npm start` to start the app.
6. Access the app at `http://localhost:3000`.


