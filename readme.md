<div align="center">
  <h1>The Nexus Sky Atlas™</h1>
  <p><strong>The Ultimate FPV Spot Discovery and Planning Application</strong></p>
  <p><em>Built by ECHO CORP</em></p>

  ![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
  ![Electron](https://img.shields.io/badge/Electron-38.1.2-47848F.svg)
  ![React](https://img.shields.io/badge/React-18.3.1-61DAFB.svg)
  ![License](https://img.shields.io/badge/license-ISC-green.svg)
</div>

---

## 🌟 Overview

**The Nexus Sky Atlas™** is a comprehensive desktop application designed for FPV (First Person View) drone pilots. Discover, explore, and plan your aerial adventures with an intuitive map interface, community-driven spot database, and intelligent planning tools.

### ✨ Key Features

- **🗺️ Interactive Map Interface** - Explore FPV spots worldwide with detailed location data
- **📍 Spot Management** - Add, edit, and organize your favorite flying locations
- **🌤️ Weather Integration** - Real-time weather data for flight planning
- **📸 Photo Gallery** - Share and view spot photos and media
- **👥 Community Features** - Connect with other FPV pilots
- **🤖 AI-Powered** - Gemini AI integration for intelligent recommendations
- **📊 Flight Planning** - Plan routes and optimize your flying experience
- **🔄 Auto Updates** - Automatic updates via Electron Updater

## 🚀 Quick Start

### Prerequisites

- **Windows 10/11** (64-bit)
- **Node.js** (v18 or higher)
- **4GB RAM** minimum
- **500MB** available storage

### Installation

#### Option 1: Download Installer (Recommended)
1. Visit the [Releases](https://github.com/mrelive/the-nexus-sky-atlas/releases) page
2. Download the latest `The-Nexus-Sky-Atlas-Setup-vX.X.X.exe` installer
3. Run the installer and follow the setup wizard
4. Launch from Start Menu or Desktop shortcut

#### Option 2: Build from Source

```bash
# Clone the repository
git clone https://github.com/mrelive/the-nexus-sky-atlas.git
cd the-nexus-sky-atlas

# Install dependencies
npm install

# Start development mode
npm run electron:dev

# Build for production
npm run dist:win
```

## 🛠️ Development

### Available Scripts

```bash
# Development
npm run dev              # Start Vite dev server
npm run electron:dev     # Start Electron in development mode

# Building
npm run build            # Build React app
npm run build:electron   # Build Electron app
npm run dist:win         # Create Windows installer

# Release
npm run release          # Create and publish GitHub release
```

### Project Structure

```
├── electron/             # Electron main process
├── src/                  # React application source
│   ├── components/       # React components
│   ├── hooks/           # Custom React hooks
│   ├── services/        # API services (Supabase, Gemini)
│   └── utils/           # Utility functions
├── public/              # Static assets
├── dist-electron/       # Built Electron app
└── release.ps1         # Release automation script
```

## 🏗️ Architecture

- **Frontend**: React 18 with TypeScript
- **Desktop**: Electron for cross-platform desktop app
- **Maps**: Leaflet with React-Leaflet integration
- **Backend**: Supabase for database and real-time features
- **AI**: Google Gemini AI for intelligent features
- **Build**: Vite for fast development and building
- **Distribution**: Electron Builder for installer creation

## 📋 System Requirements

### Minimum Requirements
- **OS**: Windows 10 (64-bit)
- **CPU**: Dual-core processor
- **RAM**: 4GB
- **Storage**: 500MB available space
- **Display**: 1920x1080 resolution

### Recommended Requirements
- **OS**: Windows 11 (64-bit)
- **CPU**: Quad-core processor or better
- **RAM**: 8GB or more
- **Storage**: 1GB available space
- **Display**: 2560x1440 resolution or higher

## 🔧 Configuration

### Environment Variables

Create a `.env.local` file in the root directory:

```env
# Supabase Configuration
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key

# Gemini AI Configuration
GEMINI_API_KEY=your_gemini_api_key
```

### API Keys Setup

1. **Supabase**: Create a project at [supabase.com](https://supabase.com)
2. **Gemini AI**: Get API key from [Google AI Studio](https://makersuite.google.com/app/apikey)

## 📦 Release Process

The project includes automated release scripts:

```bash
# Create a new release
npm run release
```

This will:
1. Prompt for version number
2. Update package.json
3. Build the application
4. Create GitHub release
5. Upload installer to releases

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Development Guidelines

- Use TypeScript for all new code
- Follow React best practices
- Write meaningful commit messages
- Test your changes thoroughly
- Update documentation as needed

## 📄 License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## 🏢 About ECHO CORP

**ECHO CORP** specializes in FPV technology and drone solutions. We build tools that enhance the FPV flying experience and connect the drone community.

### Our Mission
To empower FPV pilots with intelligent tools and comprehensive data, making every flight an unforgettable experience.

### Connect With Us
- 🌐 Website: [echocorp.com](https://echocorp.com)
- 📧 Email: contact@echocorp.com
- 🐦 Twitter: [@ECHO_CORP](https://twitter.com/ECHO_CORP)

## 🙏 Acknowledgments

- **Leaflet** - Amazing mapping library
- **Supabase** - Fantastic backend-as-a-service
- **Google Gemini** - Powerful AI capabilities
- **Electron** - Desktop app framework
- **React** - UI library that makes development enjoyable

---

<div align="center">
  <p><strong>Find your future in the skies 🛩️</strong></p>
  <p>Made with ❤️ by ECHO CORP</p>
</div>
