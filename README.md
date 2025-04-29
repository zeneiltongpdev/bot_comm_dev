# Discord Bot with AI Technology

## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation](#installation)
4. [Configuration](#configuration)
5. [Usage](#usage)
6. [Commands](#commands)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction
This project is a Discord bot powered by AI technology. It leverages natural language processing (NLP) and machine learning to provide intelligent responses and automate tasks within Discord servers.

## Features
- **AI-Powered Chat**: Responds to user queries using AI.
- **Moderation Tools**: Automates server moderation tasks.
- **Custom Commands**: Allows server admins to define custom commands.
- **Integration**: Connects with external APIs for extended functionality.
- **Learning Capabilities**: Adapts and improves over time.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/zeneiltongpdev/bot_comm_dev.git
    cd bot_comm_dev
    ```
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Set up your environment variables:
    - `DISCORD_TOKEN`: Your bot's Discord token.
    - `OPENAI_API_KEY`: API key for AI services.

## Configuration
1. Create a `.env` file in the root directory:
    ```env
    DISCORD_TOKEN=your_discord_token
    OPENAI_API_KEY=your_openai_api_key
    ```
2. Customize the `config.json` file for additional settings:
    ```json
    {
         "prefix": "!",
         "admin_roles": ["Admin", "Moderator"]
    }
    ```

## Usage
1. Start the bot:
    ```bash
    python bot.py
    ```
2. Invite the bot to your server using the OAuth2 URL generated in the Discord Developer Portal.

## Commands
- **General Commands**:
  - `!help`: Displays a list of available commands.
  - `!ping`: Checks the bot's latency.
- **AI Commands**:
  - `!ask [question]`: Asks the AI a question.
  - `!summarize [text]`: Summarizes the provided text.
- **Moderation Commands**:
  - `!ban [user]`: Bans a user.
  - `!kick [user]`: Kicks a user.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch:
    ```bash
    git checkout -b feature-name
    ```
3. Commit your changes:
    ```bash
    git commit -m "Add feature-name"
    ```
4. Push to your branch:
    ```bash
    git push origin feature-name
    ```
5. Open a pull request.

## License
This project is licensed under the [MIT License](LICENSE).
