# 42ft_transcendence 🏓

This project is a full-stack web application that implements a real-time multiplayer game, "Transcendence," inspired by the classic game of Pong. It includes a comprehensive user management system, social features, and multiple game modes.

It was our final Project to complete the 42 Wolfsburg Common Core 🎓

Deployed on Render➡️ https://four2ft-transcendence.onrender.com/

## Architecture 🏗️

![Project Architecture Diagram](./diagram.png)

### Features ✨

- **User Authentication** 🔐: Secure user registration and login system.
  - Standard email/password authentication with password hashing (bcrypt).
  - Google OAuth 2.0 for social login.
  - Two-Factor Authentication (2FA) for enhanced security.
- **User Profiles** 👤:
  - Customizable user profiles with usernames and avatars.
  - View match history and game statistics.
  - Public profiles to view other players' stats.
- **Real-time Multiplayer Gameplay** 🎮:
  - Classic Pong-style gameplay.
  - Real-time matchmaking with other players.
  - Single-player mode against an AI opponent.
  - Tournament mode for multiple players.
- **Social Features** 🤝:
  - Friends system: Add and remove friends.
  - Real-time private chat with friends.
- **Dashboard** 🖥️: A central hub to access game modes, view online friends, and manage user settings.

### Backend ⚙️

*   **Framework**: **Fastify** 🚀 is used as the web framework for Node.js, chosen for its high performance and low overhead.
*   **Language**: **Node.js** for the Server
*   **Database** 🗃️:
    *   **SQLite3**: A lightweight, file-based SQL database used for data storage.
    *   **Knex.js**: A SQL query builder used to interact with the database, allowing for portable and clean database code.
*   **Real-time Communication** 📡: **Socket.IO** is used for establishing persistent, real-time, bidirectional communication between the client and server, essential for the gameplay and chat features.
*   **Authentication & Security** 🛡️:
    *   **JSON Web Tokens (JWT)**: Used for creating access tokens to manage user sessions securely.
    *   **bcrypt**: Passwords are hashed using bcrypt before being stored in the database.
    *   **Speakeasy**: A library used to implement Time-based One-Time Passwords (TOTP) for Two-Factor Authentication (2FA).
*   **Object-Oriented Programming (OOP)**: used to structure the game logic, tournament handling, socket implementation and more.

### Frontend 🎨

*   **Build Tool/Bundler**: **Vite** ⚡ is used as the frontend build tool, providing a fast development server and optimized production builds.
*   **Language**: **TypeScript**
*   **Styling** 💅:
    *   **Tailwind CSS**: A utility-first CSS framework used for rapidly building custom user interfaces.
    *   **Plain CSS**: Used for global styles and base component styling.


## Contact
If you’d like to check out the code, just drop me a PM.


