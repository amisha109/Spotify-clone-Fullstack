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
   git clone https://github.com/francoborrelli/spotify-react-web-client.git
   cd spotify-react-web-client
   yarn install
   ```

3. **Configuration**
   - Create a Spotify App in your [Spotify Developer Dashboard](https://developer.spotify.com/dashboard)
   - Create `.env` file in project root:
   ```env
   REACT_APP_SPOTIFY_CLIENT_ID=your_client_id
   REACT_APP_SPOTIFY_REDIRECT_URL=your_redirect_uri
   ```

4. **Development**
   ```bash
   yarn start         # Start development server
   yarn build         # Create production build
   yarn test          # Run tests
   yarn lint          # Run linter
   ```

5. Access the app at `http://localhost:3000`

## 🔑 Environment Variables

| Variable | Description | Required |
|----------|-------------|----------|
| REACT_APP_SPOTIFY_CLIENT_ID | Your Spotify App Client ID | Yes |
| REACT_APP_SPOTIFY_REDIRECT_URL | OAuth redirect URL | Yes |

## 📱 Available Scripts

| Command | Description |
|---------|-------------|
| `yarn start` | Starts development server |
| `yarn build` | Creates production build |
| `yarn test` | Runs test suite |
| `yarn lint` | Runs ESLint |
| `yarn format` | Formats code with Prettier |

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🔗 Links
- [Live Demo](https://spotify-react-web-client.onrender.com/)
- [Bug Report](https://github.com/francoborrelli/spotify-react-web-client/issues)
- [Feature Request](https://github.com/francoborrelli/spotify-react-web-client/issues)
