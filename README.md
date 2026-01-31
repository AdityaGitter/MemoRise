# MemoRise - AI-Powered Chatbot for Early Alzheimer Detection

MemoRise is a MERN (MongoDB, Express.js, React.js, Node.js) based web application designed as a comprehensive digital companion to help in the early detection of Alzheimer's disease. The platform offers interactive mind games for cognitive improvement, a progress tracker to monitor memory skills, and a personal diary for capturing daily thoughts and memories. Through its AI-powered chatbot, MemoRise detects early signs of Alzheimer's and provides a personalized experience tailored to users' cognitive needs.


## Table of Contents
1. [Features](#features)
2. [Technology Stack](#technology-stack)
3. [Setup and Installation](#setup-and-installation)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [Contributing](#contributing)

## Features

- **AI-Powered Chatbot**: Detects early signs of Alzheimer's through guided conversations and activities, providing insights and support.
- **Cognitive Memory Games**: Offers various mind games specifically tailored to enhance memory and cognitive function.
- **Progress Tracker**: Monitors user performance over time, displaying progress through visual graphs and analytics.
- **Personal Diary**: Allows users to journal daily thoughts, memories, and reflections, adding a personal touch.
- **Data Security and Privacy**: Ensures sensitive information is securely stored and accessible only to authorized users.

## Technology Stack

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **AI/ML**: Integrated using custom models for early Alzheimer's detection
- **Styling**: CSS, styled-components
- **APIs**: Custom APIs for game interaction, progress tracking, and diary management

## Setup and Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/memorise.git
   cd memorise
   ```

2. **Install dependencies** for both frontend and backend:
   ```bash
   # Backend setup
   cd backend
   npm install
   
   # Frontend setup
   cd ../frontend
   npm install
   ```

3. **Environment Variables**:
   - Create a `.env` file in the root of the `backend` folder and add:
     ```plaintext
     MONGO_URI=<your_mongo_database_uri>
     JWT_SECRET=<your_jwt_secret>
     OPENAI_API_KEY=<openai_api_key_if_applicable>
     ```

4. **Run the Application**:
   ```bash
   # Backend
   cd backend
   npm start
   
   # Frontend
   cd ../frontend
   npm run dev
   ```

5. **Access the application** at `http://localhost:5173/`.

## Usage

1. **Sign Up/Login**: Register or log in to access personalized features.
2. **Chatbot Interaction**: Use the chatbot for diagnostic interactions.
3. **Play Cognitive Games**: Access various games designed to enhance memory.
4. **Track Your Progress**: View your cognitive improvement over time.
5. **Personal Diary**: Record your thoughts and memories.

## Project Structure

```
MEMORISE/
├── backend/
│ ├── config/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ ├── utils/
│ ├── .env
│ ├── .env.example
│ ├── server.js
│ ├── package.json
│ └── package-lock.json
│
├── frontend/
│ ├── public/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── services/
│ │ └── App.js
│ ├── package.json
│ └── package-lock.json
│
└── README.md
```

## Contributing

I welcome contributions from the community! Please feel free to submit issues and pull requests. For major changes, please discuss them in an issue first to ensure alignment with the project goals.
