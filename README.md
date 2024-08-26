# Apollofy

**Apolllofy** is a web application designed as a clone of Spotify. It allows users to browse, search, and manage a collection of music tracks, create playlists, and enjoy a seamless music experience. The application features secure authentication, user profile management, and an intuitive user interface.

## Content Table

1. [Features](#features)
2. [Technologies](#technologies)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Configuration](#configuration)
6. [Contributions](#contributions)
7. [License](#license)

## Features

- **Music Browsing:** Explore a wide range of music tracks and albums.
- **Search:** Find your favorite songs, artists, or albums using the search bar.
- **Playlists:** Create and manage playlists with your favorite tracks.
- **User Profile:** Secure authentication and profile management.
- **Music Streaming:** Enjoy high-quality music streaming with a responsive audio player.
- **Interface:** Clean and responsive UI built with Tailwind CSS.

## Technologies

- **Frontend:**

  - [React](https://reactjs.org/) - A JavaScript library for building user interfaces.
  - [TypeScript](https://www.typescriptlang.org/) - TypeScript enhances JavaScript with strong typing.
  - [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework for rapid UI development.
  - [Vite](https://vitejs.dev/) - A fast build tool and development server.

- **Backend:**

  - [Node.js](https://nodejs.org/) - JavaScript runtime environment for executing server-side code.
  - [TypeScript](https://www.typescriptlang.org/) - Strongly typed programming language that builds on JavaScript.
  - [Express](https://expressjs.com/) - A minimal and flexible Node.js web application framework.
  - [Prisma](https://www.prisma.io/) - An ORM that simplifies database access and management.
  - [PostgreSQL](https://www.postgresql.org/) - A powerful, open-source relational database system.

## Installation

To set up this project locally, follow these steps:

1. Clone the Repository:

   ```bash
   git clone https://github.com/yourusername/project-name.git
   ```

2. Install Dependencies:

- **Frontend:**

bash
cd frontend
npm install

- **Backend:**

bash
cd backend
npm install

3. Configure Environment Variables:

Ensure all necessary environment variables are set up. Example:

# Frontend (Vite)

VITE_API_URL=http://localhost:4000

# Backend

DATABASE_URL=postgresql://user:password@localhost:5432/apolllofy
JWT_SECRET=your_jwt_secret

4. Run the Application:

- **Frontend:**

bash
cd frontend
npm run dev

- **Backend:**

bash
cd backend
npm run dev

## Usage

Authentication: Log in or sign up to access the full features of Apolllofy.
Explore Music: Browse through the library to discover new music.
Create Playlists: Add your favorite songs to personalized playlists.
Play Music: Enjoy streaming music with the built-in audio player.
Manage Profile: Update your user profile and settings.

## Configuration

To configure the application for production:

Ensure that all environment variables are set correctly.
Make sure that the backend is properly configured to handle production traffic.
Deploy the frontend and backend to your preferred hosting services.

## Contributions

Contributions are welcome. To contribute:

1. Fork the Repository.
2. Create a Branch for your Feature or Fix.
3. Commit your Changes.
4. Push to the Branch.
5. Create a Pull Request.

## License

This project does not have a license.
