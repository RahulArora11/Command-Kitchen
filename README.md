# Voice Controlled Cooking Assistant

A hands-free cooking assistant that provides step-by-step recipe instructions with timing for each step. The assistant automatically progresses through each cooking step after the allocated time, allowing you to focus on cooking while doing other tasks in parallel.

## Features

- Voice commands to select recipes
- Step-by-step cooking instructions
- Automated timers for each cooking step
- Voice announcements of next steps
- Visual progress tracking
- Mobile-responsive design

## Technologies Used

- **Frontend**: React.js, Speech Recognition API, Web Speech API
- **Backend**: Node.js, Express.js, EJS templates
- **API**: RESTful API for recipe data

## Project Structure

```
Voice_Controlled_Cook_Assistant/
├── backend/             # Express server and API
│   ├── server.js        # Main server file
│   ├── views/           # EJS templates
│   └── package.json     # Backend dependencies
│
├── frontend/            # React frontend application
│   ├── public/          # Static assets
│   ├── src/             # React source code
│   │   ├── components/  # React components
│   │   ├── App.js       # Main React application
│   │   └── App.css      # Application styles
│   └── package.json     # Frontend dependencies
│
└── README.md            # Project documentation
```

## Setup and Installation

1. Clone the repository:
   ```
   git clone <repository-url>
   cd Voice_Controlled_Cook_Assistant
   ```

2. Install backend dependencies:
   ```
   cd backend
   npm install
   ```

3. Install frontend dependencies:
   ```
   cd ../frontend
   npm install
   ```

4. Start the backend server:
   ```
   cd ../backend
   node server.js
   ```

5. Start the frontend development server:
   ```
   cd ../frontend
   npm start
   ```

6. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

## Usage

1. Allow microphone access when prompted by the browser
2. Click the "Start Voice Control" button
3. Say the name of a dish you want to cook (e.g., "pasta", "omelette", "chicken curry")
4. Follow the step-by-step instructions
5. The application will automatically move to the next step after the timer completes

## Supported Recipes

Currently, the application includes the following recipes:
- Spaghetti Aglio e Olio
- Basic Omelette
- Simple Chicken Curry

More recipes can be added to the `recipes` object in the `backend/server.js` file.

## Future Enhancements

- Add user accounts to save favorite recipes
- Allow users to add their own recipes
- Implement voice commands for navigating steps manually
- Add ingredient quantity adjustment based on serving size
- Integrate with smart home devices for temperature control

## License

This project is licensed under the MIT License. 