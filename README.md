# User Profile API

## Overview
This project is a RESTful API for managing user profiles, designed as an interview assignment. It allows users to register, retrieve, and update their profiles using JWT-based authentication. The API is built with Express.js and MongoDB, ensuring secure and scalable user data management.

## Features
- **User Registration:** Create new user profiles with name, email, address, and a hashed password.
- **JWT Authentication:** Secure endpoints so that users can only access and update their own profiles.
- **Profile Management:** Retrieve and update user profiles, including optional fields like bio and profile picture URL.
- **Error Handling:** Robust error responses to ensure clarity during development and debugging.

## Technologies Used
- **Backend:** Express.js
- **Database:** MongoDB
- **Authentication:** JSON Web Tokens (JWT)
- **Libraries:** bcryptjs, dotenv, cors, multer

## Setup and Installation

### Prerequisites
- **Node.js and npm:** Ensure Node.js is installed on your machine.
- **MongoDB:** MongoDB Atlas

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/user-profile-api.git
   cd user-profile-api

## Postman Documentation

A Postman collection for the User Profile API is provided in the file [`postman_collection.json`](postman_collection.json).

**To import the collection:**
1. Open Postman.
2. Click on the **Import** button.
3. Drag and drop the `postman_collection.json` file or use the file selector.
4. The collection will be added to your Postman collections list.
5. You can then run the pre-configured requests for User Registration, Profile Retrieval, and Profile Update.
