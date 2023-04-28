## ⚠️ Warning

GPT has the ability to generate text responses on a wide range of topics. However, due to the nature of the content that it can generate, it may not be appropriate for **minors**.

# Discord GPT-3 Bot

This bot uses OpenAI's GPT-3 to generate responses based on prompts from a JSON file and interacts with users on Discord.

## Features

- Generate responses based on GPT-3 model
- Custom statuses that the bot cycles through
- Commands to change bot's profile picture, username, and more

## Installation

1. Clone the repository:
```
git clone https://github.com/mishalhossin/Gpt3-chatbot-discord.git
```

2. Install dependencies:
```
pip install -r requirements.txt
```

3. Create a `.env` file with your OpenAI API key and Discord bot token :
```
OPENAI_API_KEY=your_api_key_here
DISCORD_TOKEN=your_discord_bot_token
```
4. Run the bot:
linux :
```
python3 main.py
```
windows:
```
py main.py
```

## Usage

To use the bot, invite it to a Discord server and use commands like `!ping`, `!changeusr`, etc.
For example, to change the bot's username, use:
```
!changeusr NewBotName
```
and to change profile picture use :
```
!pfp linktonewpfp.com/image.png
```
For more commmands use `!welp` or `!help`

