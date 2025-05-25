# DANARA - Cold Wallet Desktop App

A secure, offline-first cryptocurrency wallet built with Tauri, React, and modern web technologies.

## Features

- 🔒 **Offline Security**: Generate and manage wallets completely offline
- 🎨 **Modern UI**: Glassmorphism design with smooth animations
- 🔌 **Hardware Integration**: Connect to custom hardware wallets via USB
- 💾 **Secure Storage**: Encrypted storage on removable devices
- 🌙 **Dark Mode**: Beautiful dark theme with glass effects
- ⚡ **Fast Performance**: Built with Rust backend for optimal speed

## Tech Stack

- **Frontend**: React, Tailwind CSS, Framer Motion
- **Backend**: Rust with Tauri framework
- **Crypto**: BIP39, Bitcoin libraries
- **UI**: Glassmorphism with 3D elements

## Quick Start

1. **Prerequisites**
   - Node.js 18+
   - Rust 1.70+
   - Platform-specific build tools (see Tauri docs)

2. **Install Dependencies**
   \`\`\`bash
   npm install
   \`\`\`

3. **Run Development Server**
   \`\`\`bash
   npm run tauri dev
   \`\`\`

4. **Build for Production**
   \`\`\`bash
   npm run tauri build
   \`\`\`

## Architecture

The app follows a secure architecture with:
- Rust backend for cryptographic operations
- React frontend with TypeScript
- USB communication for hardware wallets
- Encrypted file storage for wallet data

## Security Features

- Offline-first design
- BIP39 mnemonic generation
- Hardware wallet integration
- Encrypted storage
- No network dependencies for core functions

## License

MIT License - see LICENSE file for details
