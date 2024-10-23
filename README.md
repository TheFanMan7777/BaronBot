# BaronBot

BaronBot is a multi-functional Discord bot designed to enhance your server experience. It features message moderation, economy system, and fun interactions for users. This bot includes commands for balance checking, transferring currency, logging deleted messages, and more.

## Features

- **Message Moderation**: Automatically delete Discord invite links, time out users, and ban repeat offenders.
- **Economy System**: Earn and spend BaronBucks through various commands and interactions.
- **Logging**: Keep track of deleted messages, including images, in a designated log channel.
- **Interactive Games**: Engage users with fun mini-games like Blackjack.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) v16.6.0 or higher
- [Discord.js](https://discord.js.org/) v13 or higher
- [Axios](https://axios-http.com/)

### Installation

1. **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/BaronBot.git
    cd BaronBot
    ```

2. **Install dependencies:**
    ```sh
    npm install
    ```

3. **Set up environment variables:**

   Create a `.env` file in the root directory and add the following:
    ```env
    TOKEN=your-bot-token
    GUILD_ID=your-guild-id
    LOG_CHANNEL_ID=your-log-channel-id
    ```

4. **Run the bot:**
    ```sh
    node index.js
    ```

### Command List

- **Balance**
  - Check your current balance.
  - Usage: `!balance`
  
- **Transfer**
  - Transfer BaronBucks to another user.
  - Usage: `!transfer @user amount`

- **Work**
  - Earn BaronBucks by working.
  - Usage: `/work`

- **Blacklist**
  - Add or remove users/roles from the blacklist.
  - Usage: `/blacklist @user|@role`

- **Status**
  - Set the bot status.
  - Usage: `/status type text`

## Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss your ideas.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Discord.js](https://discord.js.org/)
- [Node.js](https://nodejs.org/)
- [Axios](https://axios-http.com/)

## Contact

For support or inquiries, contact [aidenjohn284@gmail.com](mailto:aidenjohn284@gmail.com).

