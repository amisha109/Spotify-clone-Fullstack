# 🎵 Spotify React Web Client

A modern Spotify web client built with React that allows you to control and enjoy your Spotify music seamlessly.

> [!IMPORTANT]
> Spotify Premium subscription is required for playback functionality.

## 🚀 Features

### Core Features
- Real-time music playback via Spotify Playback SDK
- Full playback controls (play, pause, skip, volume, shuffle, repeat)
- Search and browse songs, artists, albums, and playlists
- Create, edit, and manage playlists
- Access to saved music library (playlists, albums, liked songs)
- Multi-device playback control
- Artist and album page navigation
- Social features (follow/unfollow artists)

### Technical Features
- Responsive and modern UI design
- Real-time state management
- OAuth2 authentication with Spotify
- Efficient data caching
- Cross-platform compatibility
- Error handling and recovery
- Offline mode support

## 🛠 Tech Stack

### Frontend
- **React 18** - UI component library
- **TypeScript** - Type-safe development
- **Redux Toolkit** - State management
- **React Router** - Navigation and routing
- **Styled Components** - Styling solution
- **Material UI** - UI component framework

### APIs & SDKs
- **Spotify Web API** - Data fetching and manipulation
- **Spotify Playback SDK** - Real-time music playback
- **Web Audio API** - Audio processing

### Development Tools
- **Vite** - Build tool and development server
- **ESLint** - Code linting
- **Prettier** - Code formatting
- **Jest** - Testing framework
- **React Testing Library** - Component testing

## ⚙️ Setup & Installation

1. **Prerequisites**
   - Node.js (v16 or higher)
   - Yarn package manager
   - Spotify Premium account
   - Spotify Developer account

2. **Clone and Install**
   ```bash
   git clone https://github.com/amisha109/Spotify-clone-Fullstack.git
   cd Spotify-clone-Fullstack
   yarn install
   ```

3. **Configuration**
   - Create a new application in the [Spotify Developer Dashboard](https://developer.spotify.com/dashboard)
   - Set up the OAuth settings in your Spotify App:
     - Add `http://localhost:3000` to Redirect URIs
     - Note down your Client ID
   - Create `.env` file in project root:
   ```env
   REACT_APP_SPOTIFY_CLIENT_ID=your_spotify_client_id
   REACT_APP_SPOTIFY_REDIRECT_URL=http://localhost:3000
   ```

4. **Development Commands**
   ```bash
   # Start development server
   yarn start

   # Create production build
   yarn build

   # Run tests
   yarn test

   # Run linter
   yarn lint

   # Format code
   yarn format
   ```

5. **Verify Installation**
   - Start the development server with `yarn start`
   - Open your browser to `http://localhost:3000`
   - You should see the login screen
   - Log in with your Spotify Premium account

## 🔑 Environment Variables

| Variable | Description | Required | Default |
|----------|-------------|----------|---------|
| REACT_APP_SPOTIFY_CLIENT_ID | Your Spotify App Client ID | Yes | - |
| REACT_APP_SPOTIFY_REDIRECT_URL | OAuth callback URL | Yes | http://localhost:3000 |

## 🚀 Available Scripts

| Command | Description |
|---------|-------------|
| `yarn start` | Starts development server on port 3000 |
| `yarn build` | Creates optimized production build |
| `yarn test` | Runs test suite with Jest |
| `yarn lint` | Runs ESLint for code quality |
| `yarn format` | Formats code with Prettier |

## 🔧 Troubleshooting

### Common Issues

1. **Playback Not Working**
   - Ensure you have an active Spotify Premium subscription
   - Check if you're logged in with the correct account
   - Verify your Client ID in the `.env` file

2. **Build Errors**
   - Run `yarn clean` to clear cache
   - Delete `node_modules` and run `yarn install` again
   - Ensure you're using Node.js v16 or higher

3. **Authentication Issues**
   - Verify your Spotify Developer Dashboard settings
   - Check if redirect URI matches exactly
   - Clear browser cookies and try again
