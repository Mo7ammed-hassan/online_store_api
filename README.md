# Online Store API

This repository contains the code for the backend API of an online store, built using Node.js and Express. The API provides endpoints for managing products, categories, user authentication, and order processing, serving as the backend for the online store's client and admin panel applications.

## Table of Contents
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Running the API](#running-the-api)
- [API Endpoints](#api-endpoints)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)

## Features
- **Product Management:** Create, read, update, and delete products.
- **Category Management:** Handle categories for organizing products.
- **User Authentication:** Secure authentication and authorization for users.
- **Order Processing:** Manage orders, including creation, updating, and retrieval.
- **Image Uploads:** Handle image uploads for products using Multer middleware.

## Project Structure
The project is organized into several key directories:


## Getting Started

### Prerequisites
- **Node.js:** [Install Node.js](https://nodejs.org/)
- **MongoDB:** Make sure you have a MongoDB instance running or use a cloud service like MongoDB Atlas.

### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Mo7ammed-hassan/online_store_api.git
    cd online_store_api
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Create a `.env` file in the root directory and add your environment variables:
    ```bash
    PORT=5000
    MONGODB_URI=your_mongodb_uri
    JWT_SECRET=your_secret_key
    ```

## Running the API
To start the API server:

```bash
npm start
