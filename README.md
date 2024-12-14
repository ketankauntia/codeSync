# codeSync - Real-time Code Collaboration

codeSync is a real-time code collaboration web application that allows multiple users to collaborate on code in the same virtual room. It's built using the MERN (MongoDB, Express.js, React, Node.js) stack and Socket.IO for real-time communication.

## Technologies Used

- Express.js: Handling API requests.
- React: Building the front-end interface.
- Node.js: Running the server.
- Socket.IO: Enabling real-time communication.
- uuid: Generating unique room IDs.
- CodeMirror: Providing the code editor.
- Bootstrap : Css Framework for ui.

## Features

- Create or join a virtual "room" by entering a room ID.
- Set your username to identify yourself in the room.
- Real-time code collaboration with other users in the same room.
- Changes made by one user are instantly reflected on all connected clients.
- Code highlighting and editor customization options.

## Usage

1. Open the CodeSync .
2. Enter a Room ID or generate a new one.
3. Set your username.
4. Start collaborating with others in the same room.

## Development

If you want to run codeSync locally or contribute to its development, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/ketankauntia/codeSync.git
   cd codeSync
   ```

2. Install dependencies:
   ```
   npm i
   ```
3. Start the development server:
   ```
   npm start
   ```
