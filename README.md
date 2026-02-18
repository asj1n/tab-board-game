# Tâb - Board Game

Web-based version of the ancient Egyptian game [Tâb](https://en.wikipedia.org/wiki/T%C3%A2b), a 2-player strategy board game played on a 4xN board (odd N columns between 7 and 15), where players roll dice, move pieces, and capture opponents' until only one player has pieces remaining
- Designed to support both single-player mode against an AI opponent and online multiplayer (PvP)
- Frontend app built with JavaScript, HTML, and CSS following a Single Page Application (SPA) architecture, featuring dynamic panels for game setup, rules, rankings, authentication, and gameplay
- Backend server developed in Node.js, handling HTTP requests, real-time updates via Server-Sent Events (SSE), and a simplified persistent storage of users and rankings through serialized files
