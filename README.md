# Bitasmbl-Lightweight-Chat-App-(No-Auth)-16825b-Empty

## Description
Build a web application that allows users to join anonymous chatrooms and exchange messages in real-time using WebSockets. The focus is on fast communication, simple interface, and responsive updates without requiring user registration.

## Tech Stack
- GraphQL
- Ember.js
- SignalR

## Requirements
- Allow users to join chatrooms without authentication
- Send and receive messages in real-time using WebSockets
- Display messages with timestamps and user identifiers (anonymous)
- Handle multiple chatrooms simultaneously
- Gracefully handle disconnected users and reconnections

## Installation
bash
git clone https://github.com/MrBitasmblTester2/Bitasmbl-Lightweight-Chat-App-(No-Auth)-16825b-Empty.git
cd Bitasmbl-Lightweight-Chat-App-(No-Auth)-16825b-Empty


## Usage
- Start the backend and WebSocket/SignalR server
- Start the Ember.js frontend and open in a browser

## Implementation Steps
1. Define GraphQL schema for chatrooms and messages.
2. Set up SignalR hub for real-time messaging over WebSockets.
3. Implement GraphQL resolvers integrating with SignalR.
4. Build Ember.js routes and components for chatroom listing and views.
5. Connect Ember.js to GraphQL API for loading chatrooms and messages.
6. Use SignalR in Ember.js to send and receive messages in real-time.
7. Display messages with timestamps and anonymous user identifiers.
8. Handle multiple chatrooms, disconnections, and reconnections in the client.