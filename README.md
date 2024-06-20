# CosmoChat UI

Overview:
CosmoChat UI is the frontend application that enables users to engage in chat sessions with an AI chatbot powered by OpenAI's language model. The primary objective is to offer a seamless platform for users to interact with the chatbot, ask questions, and receive responses naturally. It incorporates features such as activity tracking, session ending, and session management.
![alt text](https://ai.radicalai.app/_next/image?url=https%3A%2F%2Ffirebasestorage.googleapis.com%2Fv0%2Fb%2Fradicalx-68127.appspot.com%2Fo%2FCosmoChat%252FCosmo%2520Chat.png%3Falt%3Dmedia%26token%3D0b05e20c-557b-48cf-99c9-cade4b6865ff&w=1920&q=75)
Technologies and Tools used:
React.js
Material UI
Axios
OpenAI
Available Scripts
In the project directory, we can run:

npm start:
Runs the react app in the development mode. Open http://localhost:3000 to view it in our browser.
The page will reload when we make changes.

node ./server.js:
Runs the server.js file which start server that will store the chats sessions in data/db.json file in json format. Server will be running on port 3500.

Project Setup Instructions:
To set up CosmoChatUI, follow these steps:

Clone the repository to your local machine.

To clone run:
git clone https://github.com/Viraj5903/CosmoChatUI.git
Ensure you have Node.js and npm installed:

Download and install Node.js if you haven't already.
Navigate to the root directory of the project:

To navigate to the root directory of the project, run:
cd CosmoChatUI
Install Dependencies:

To install required dependencies, run:
npm install
Add your OpenAI API key:

Get your OpenAI API key from OpenAI
Create a .env file in the root directory of the project.
Add the following line to the .env file, replacing {YOUR_API_KEY} with your actual API key:
REACT_APP_OPENAI_API_KEY={YOUR_API_KEY}
Run Server:

To run the server that store that chats session inside the data/db.json file in json format. Run:
node ./server.js
Start React Application:

To start react application. Run:
npm start
