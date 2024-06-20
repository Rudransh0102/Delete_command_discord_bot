
---

# Discord Bot Command Remover

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Discord](https://img.shields.io/discord/CHANNEL_ID.svg?label=discord)](https://discord.gg/YOUR_INVITE_LINK)

Easily delete all registered slash commands for any Discord bot using this simple script.

## 📋 Table of Contents

- [About](#about)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Usage](#usage)
- [License](#license)
- [Contributing](#contributing)
- [Give a star!](#Give-a-Star)
- [Acknowledgements](#acknowledgements)

## 📖 About

This script allows you to delete all guild-based and global slash commands for your Discord bot. It uses the Discord.js library to interact with the Discord API.

## 🚀 Getting Started

Follow these instructions to set up and use the script.

### Prerequisites

- Node.js (v14.0.0 or later)
- NPM (v6.0.0 or later)
- Discord bot with proper permissions

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/discord-bot-command-remover.git
   cd discord-bot-command-remover
   ```

2. Install the required packages:
   ```bash
   npm install
   ```

3. Fill the `config.json` file in the root directory by your bot's credentials:
   ```json
   {
     "clientId": "YOUR_CLIENT_ID",
     "guildId": "YOUR_GUILD_ID",
     "token": "YOUR_BOT_TOKEN"
   }
   ```

### Usage

1. Run the script:
   ```bash
   node index.js
   ```

2. The script will attempt to delete all registered slash commands for your bot. Check the console for success or error messages.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/Rudransh0102/discord-bot-command-remover/issues) if you want to contribute.

## ⭐ Give a Star!
If you found this repository useful, please consider giving it a star on GitHub. It helps others find the project and encourages the development of new features!

## 🙏 Acknowledgements

- [Discord.js](https://discord.js.org/)
- [Node.js](https://nodejs.org/)

---
