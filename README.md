In5 Chatbot

This project consists of a chatbot built using React for the frontend and an Express server for the backend. It utilizes OpenAI's GPT-3.5 for natural language processing and responses.


Features
Chat Interface: Users can interact with the chatbot through a simple text input field.
Real-time Responses: The chatbot provides immediate responses based on the input.
Role-based Messaging: Messages are distinguished between user and system roles.
Installation
Prerequisites
Node.js (v14.17.0 or higher)
npm (v6.14.13 or higher)
Setup Instructions
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/in5-chatbot.git
cd in5-chatbot
Install Dependencies:

For the frontend:

bash
Copy code
cd frontend
npm install
For the backend:

bash
Copy code
cd backend
npm install
Start the Development Servers:

For the frontend:

bash
Copy code
cd frontend
npm run dev
For the backend:

bash
Copy code
cd backend
npm start
Access the Application:

The frontend will be accessible at http://localhost:3000.
The backend will be running on http://localhost:8000.
Technologies Used
Frontend:

React
ReactDOM
Vite
ESLint
Backend:

Express
OpenAI
Body-parser
CORS
Folder Structure
frontend/: Contains the React frontend code.
backend/: Includes the Express server and OpenAI integration.
How to Use
Open the application in your browser.
Start typing messages in the chat input field.
Interact with the chatbot and observe the responses.
Contribution
Contributions are welcome! If you'd like to improve this project, feel free to fork it and submit a pull request. Any contributions you make are greatly appreciated.

License
This project is licensed under the MIT License - see the LICENSE file for details.
