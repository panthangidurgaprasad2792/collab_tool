# REAL-TIME-COLLABORATION-TOOL

## Description

This project is a real-time collaboration tool developed using WebSocket, Node.js, React,  designed to facilitate seamless collaboration between multiple users on shared documents or workspaces. The primary goal was to build an interactive and synchronized platform for remote teams, students, or professionals, allowing them to edit content, exchange messages, and upload files simultaneously — all without page reloads.

The tool enables instant updates, so all users see changes reflected in real-time, improving team productivity and communication. Its user-centric design focuses on responsiveness, live feedback, and accessibility across devices.

## Tools & Technologies

WebSocket: Enables real-time bi-directional communication between the server and clients. Used to broadcast live changes (edits, messages, file uploads) instantly across all connected users.

Node.js + Express.js: Acts as the backend server. Handles routing, session management, authentication, and WebSocket integration for scalable and efficient performance.

React: Powers the frontend. The component-based architecture ensures smooth state updates, live workspace rendering, and responsive UI.

## Key Features

Real-Time Editing: Users can work collaboratively on shared content. Edits are synchronized live using WebSocket broadcasting.

Shared Workspace: Supports multiple users editing, chatting, and uploading files in the same environment — with all actions reflected in real time.

Live Chat: Built-in messaging system for quick communication during collaboration.

## Design Philosophy

The UI follows a minimalist, functional design, emphasizing clarity and ease of use. The layout separates the editing panel, file sharing area, and chat section, allowing users to multitask efficiently. Responsive design principles were applied using CSS Flexbox and Grid, ensuring compatibility across desktops, tablets, and mobile devices.

React’s dynamic rendering keeps the interface fast and interactive, while multi-user edits are efficiently handled to maintain app consistency without reloading.

## Installation

Prerequisites: Node.js, npm

# Clone the repository

  git clone https://github.com/Rajeshwari-parman/REAL-TIME-COLLABORATION-TOOL.git

# Backend Setup

  cd REAL-TIME-COLLABORATION-TOOL/server

  npm install

  node server.js

# Frontend Setup

  cd ../client
  
  npm install
  
  npm start
  
Access the app at: http://localhost:5001

## Output

1. Collaborative Tool UI:
   
  ![Image](https://github.com/user-attachments/assets/c88015c0-c37b-43d0-8f0d-c9d2f50a74c3)

2. User 1 Typing (Left Side):

  ![Image](https://github.com/user-attachments/assets/0d1ca412-3c11-4a20-af3c-456977999031)

3. User 2 Typing (Right Side):

  ![Image](https://github.com/user-attachments/assets/86229da6-604a-47bd-8ff6-5b2d3d2e282e)

