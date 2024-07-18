# BFit - Fitness Tracking Web Application

## Overview
BFit is a comprehensive fitness tracking web application built using the MERN (MongoDB, Express.js, React, Node.js) stack. It allows users to log workouts, set fitness goals, and access a library of exercises.

## Features
1. **Workout Tracking**
   - Log workouts with exercise types, sets, reps, weights, and durations
   - View workout history and progress

2. **Goal Setting and Achievement Tracking**
   - Set personal fitness goals (e.g., target weights, distances)
   - Track progress towards goals
   - Receive notifications on goal achievements

3. **Exercise Library**
   - Access a comprehensive library of exercises
   - Search for exercises by name, muscle group, or equipment
   - View detailed exercise descriptions, images, and proper form guidelines

4. **User Authentication**
   - Secure user registration and login
   - Personalized dashboard for each user

## Technologies Used
- Frontend: React.js
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JSON Web Tokens (JWT)
- State Management: Redux (optional, if used)
- Styling: CSS3, Sass, or a UI library like Material-UI or Bootstrap

## Installation and Setup
1. Clone the repository
   ```
   git clone https://github.com/your-username/bfit.git
   cd bfit
   ```

2. Install dependencies for backend and frontend
   ```
   cd backend
   npm install
   cd ../frontend
   npm install
   ```

3. Set up environment variables
   - Create a `.env` file in the backend directory
   - Add necessary variables (e.g., MongoDB URI, JWT secret)

4. Run the application
   ```
   # In the backend directory
   npm start

   # In the frontend directory
   npm start
   ```

5. Access the application at `http://localhost:3000`

## API Endpoints
- `POST /api/workouts`: Log a new workout
- `GET /api/workouts`: Retrieve workout history
- `POST /api/goals`: Set a new fitness goal
- `GET /api/goals`: Retrieve user goals
- `GET /api/exercises`: Fetch exercise library
- `GET /api/exercises/:id`: Fetch details of a specific exercise

## Future Enhancements
- Integration with fitness wearables for automatic workout tracking
- Social features for connecting with friends and sharing achievements
- Customizable workout plans based on user goals
- Nutrition tracking and meal planning

## Contributing
Contributions to improve BFit are welcome. Please feel free to submit a pull request or open an issue for discussion.

## Contact
Ahmed Abd-ur-Rahman - i210404@nu.edu.pk

Project Link: [https://github.com/Asquarer02/BFit-MERN-Stack](https://github.com/Asquarer02/BFit-MERN-Stack)