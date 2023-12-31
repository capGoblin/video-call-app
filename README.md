# OneStop - Video Collaboration Platform 💻🚀

OneStop is a collaborative Video-Collaboration Platform designed for real-time communication and collaboration among remote teams. The application integrates features like Video Calls with Whiteboard, Whitesheet, and Code Editor Live to collaborate with a seamless switch between them.

## Features 🌟

OneStop offers a comprehensive suite of features enabling seamless remote collaboration:

- **Real-time Video Calls (webRTC implementation from scratch):** Seamlessly connect multiple participants in video calls.
- **Simple Collaborative Whiteboard (Excalidraw - collab feature implemented from scratch):** Collaborate visually with a robust whiteboard for collective brainstorming and creativity.
- **Whitesheet Collaboration (Quill - collab feature implemented from scratch):** Utilize a separate whitesheet for additional collaborative space and brainstorming.
- **Live Collaborative Code Editor (Monaco - collab feature implemented from scratch):** Empower collaborative programming through a real-time code editor.

## Tech Stack ⚙️

- **Frontend:** React.js, TailwindCSS
- **Backend:** Node.js, Express
- **Real-time Communication:** WebRTC, Socket.io
- **Database:** MongoDB Atlas

## Local Development 🛠️

### Setup

```bash
git clone https://github.com/your-username/OneStop.git
```

```bash

# Install dependencies for client
yarn install

# Install dependencies for server
cd server
yarn install
```

```bash
# Start the frontend server
yarn run dev

# Start the backend server
cd server
yarn start
```

## Accessing the Application 🌐

Access the application at [one-stop-tau.vercel.app](one-stop-tau.vercel.app).
(works for Chrome, but Edge and Safari face issues w/ the webRTC API navigator.getUserMedia camera doesn't load)

## About ℹ️

OneStop is a real-time Video Collaboration Platform crafted with React.js, Node.js, Express, Socket.io, and WebRTC. It enables seamless remote collaboration through video calls, whiteboard, whitesheet, and code editor. Designed for enhanced productivity, it showcases proficiency in robust communication protocols.
