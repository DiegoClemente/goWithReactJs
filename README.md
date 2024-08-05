# AMA Room App

Welcome to the AMA (Ask Me Anything) Room App! This project leverages some of the most popular and modern technologies in the market to create a dynamic, real-time question-and-answer platform.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The AMA Room App is a web application designed to facilitate interactive Q&A sessions. Users can join rooms, ask questions, and receive answers in real time. This project showcases the integration of various front-end and back-end technologies to deliver a seamless user experience.

## Features

- **Real-time Q&A:** Interact with questions and answers in real-time using WebSockets.
- **User Authentication:** Secure login and registration process.
- **Room Management:** Create and join multiple AMA rooms.
- **Responsive Design:** Optimized for all devices using Tailwind CSS.
- **Type Safety:** Built with TypeScript for robust and maintainable code.

## Technologies Used

- **Frontend:**
  - [Vite](https://vitejs.dev/): Next Generation Frontend Tooling
  - [Tailwind CSS](https://tailwindcss.com/): A utility-first CSS framework
  - [TypeScript](https://www.typescriptlang.org/): JavaScript with syntax for types
- **Backend:**
  - [Go Chi](https://github.com/go-chi/chi): Lightweight, idiomatic and composable router for building Go HTTP services
  - [WebSockets](https://developer.mozilla.org/en-US/docs/Web/API/WebSockets_API): For real-time communication
  - [SQL](https://en.wikipedia.org/wiki/SQL): For database management
  - [PostgreSQL](https://www.postgresql.org/): Advanced open-source relational database

## Installation

### Prerequisites

Make sure you have the following installed:
- [Node.js](https://nodejs.org/) (v14 or later)
- [Go](https://golang.org/) (v1.16 or later)
- [PostgreSQL](https://www.postgresql.org/)

### Frontend

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/ama-room-app.git
   cd ama-room-app/frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm run dev
   ```

### Backend

1. Navigate to the backend directory:

   ```bash
   cd ../backend
   ```

2. Install Go dependencies:

   ```bash
   go mod tidy
   ```

3. Set up the PostgreSQL database and update the database configuration in the `.env` file.

4. Run the backend server:

   ```bash
   go run main.go
   ```

## Usage

Once the frontend and backend servers are running, you can access the AMA Room App by navigating to `http://localhost:3000` in your web browser.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add new feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.
