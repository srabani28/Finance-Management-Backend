# Finance Management Backend

## Overview
This is the backend service for the Finance Management application. It provides APIs for managing budgets and expenses, handling user authentication, and securely storing financial data.

## Technologies Used
- **Node.js** - Runtime environment
- **Express.js** - Web framework for handling routes and API requests
- **MongoDB** - NoSQL database for storing user and financial data
- **JWT (JSON Web Token)** - Used for authentication and security

## Live Backend API
The backend is deployed on Render and can be accessed at:  
[Finance Management Backend](https://finance-management-backend-uvjg.onrender.com)

## Repository
The source code is available on GitHub:  
[Finance Management Backend](https://github.com/srabani28/Finance-Management-Backend)

## Getting Started
To set up and run the backend locally, follow these steps:

1. Clone the repository:
   ```sh
   git clone https://github.com/srabani28/Finance-Management-Backend.git
   cd Finance-Management-Backend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file in the root directory and add the required environment variables:
   ```env
   MONGO_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   PORT=5000
   ```
4. Start the server:
   ```sh
   npm start
   ```
5. The server will run on [http://localhost:5000](http://localhost:5000)

## API Endpoints

### Authentication
- `POST /api/auth/register` - Register a new user
- `POST /api/auth/login` - User login and token generation

### Budget & Expenses
- `GET /api/budget` - Get the user's budget details
- `POST /api/budget` - Add income or expense
- `DELETE /api/budget/:id` - Delete an entry

## Deployment
The backend is deployed using **Render**.

## Contributing
If you would like to contribute, feel free to fork the repo and submit a pull request!

## License
This project is open-source and free to use.

---

Feel free to update the README as your backend evolves!
