# Album Finder
Album Finder is a web application that allows users to search for any artist and explore all their albums instantly.
It uses the Spotify Web API to fetch real-time artist and album data and presents it with a clean, modern UI.

## Features
- Search for any artist
- View all albums with cover images
- Display release dates
- Direct links to album pages on Spotify
- Simple and elegant dark-themed UI
- Built with Vite for fast development and optimized builds
- Responsive layout

## Tech Stack

| Technology        | Used For                        |
|------------------|---------------------------------|
| **React**        | Frontend UI framework           |
| **Vite**         | Development & build tool        |
| **Spotify Web API** | Fetching artist + album data |
| **React-Bootstrap** | UI components               |
| **CSS**          | Custom styling                  |

## Installation & Setup

### Clone the repository
  ```bash
  git clone https://github.com/05-Jagriti/Album-Finder.git
  cd Album-Finder
  ```

### Install dependencies
  ```bash
  npm install
  ```

### Create a .env file in the project root
  ```bash
  VITE_CLIENT_ID=your_spotify_client_id
  VITE_CLIENT_SECRET=your_spotify_client_secret
  ```

### Start the local development server
  ```bash
  npm run dev
  ```

## Spotify API Setup
1. Visit the Spotify Developer Dashboard:
   [https://developer.spotify.com/dashboard]
2. Create an app
3. Copy:
      Client ID
      Client Secret
4. Add these values to your ```.env``` file or Vercel environment variables
