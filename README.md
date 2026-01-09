# Bitasmbl-Lightweight-Chat-App-No-Auth-835c10

## Description
Build a web application that allows users to join anonymous chatrooms and exchange messages in real-time using WebSockets. The focus is on fast communication, simple interface, and responsive updates without requiring user registration.

## Tech Stack
- Express.js
- React
- Socket.IO

## Requirements
- Express.js
- React
- Socket.IO

## Installation
bash
git clone https://github.com/he1snber8/Bitasmbl-Lightweight-Chat-App-No-Auth-835c10.git
cd Bitasmbl-Lightweight-Chat-App-No-Auth-835c10
npm install
cd client
npm install


## Usage
bash
# in root
npm run server
# in client
npm start


## Implementation Steps
1. Initialize Express.js server and integrate Socket.IO.
2. Create chatroom namespaces or rooms with Socket.IO.
3. Broadcast messages to all clients in a room.
4. Initialize React app for the chat UI.
5. Connect React components to Socket.IO client.
6. Handle joining rooms and sending messages in React.
7. Ensure responsive UI updates on new messages.