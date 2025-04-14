
**<p align='center'>Visit the live website : <a href="https://wander-abode.onrender.com/listings">🏡 [Wander Abode]</a></p>**


# Wander Abode

A full-stack web application inspired by Airbnb, where users can browse property listings, add their own listings, sign up, log in, and leave reviews.

## Features
- User authentication (Sign Up, Login, Logout)
- Browse available property listings
- Add new property listings
- Edit and delete personal listings
- Leave reviews on listings
- Responsive design for a seamless user experience

## Technologies Used
- **Backend**: Node.js, Express.js, MongoDB, Mongoose
- **Frontend**: HTML, CSS, JavaScript, EJS, Bootstrap
- **Authentication**: Passport.js

## Live Demo
Check out the live version of Wander Abode here:  
[![Wander Abode](https://img.shields.io/badge/Live-Demo-brightgreen)](https://wander-abode.onrender.com/listings)

## Installation & Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/Rohit15504/Wander_Abode.git
   cd Wander_Abode
   ```
2. **Install dependencies:**

  ```bash
  npm install
   ```
3. **Set up the environment variables:**

    A. Create a `.env` file in the root directory.
    
    B. Add the required environment variables:
     - `MONGO_URI=<your_mongodb_connection_string>`
     - `SESSION_SECRET=<your_secret_key>`
     - Other necessary environment variables as needed.

4. **Start the development server:**

  ```bash
  npm start
   ```
5. **Open the application in your browser:**

  ```bash
  http://localhost:8081
   ```

## Project Structure
```
Wander_Abode/
│-- models/ # Mongoose models (User, Listing, Review) 
│-- routes/ # Express routes for authentication, listings, and reviews
│-- views/ # EJS templates for frontend rendering
│-- public/ # Static files (CSS, JS, Images)
│-- app.js # Main server file
│-- package.json # Dependencies and scripts 
```



## License
This project is licensed under the **MIT License**.
