# kbot

A functional Telegram bot built with Go using Cobra CLI framework and telebot.v3 library. This bot can handle messages from users and respond to them accordingly.

**Bot Link**: t.me/alexshamrai_bot

## Build and Run Locally

### Prerequisites
- Go 1.24.5 or later
- Telegram Bot Token (get it from [@BotFather](https://t.me/BotFather))

### Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/alexshamrai/kbot.git
   cd kbot
   ```

2. **Install dependencies:**
   ```bash
   go mod download
   ```

3. **Set your bot token:**
   ```bash
   export TELE_TOKEN="your_bot_token_here"
   ```

4. **Build the application with setting the version:**
   ```bash
   go build -ldflags "-X="github.com/alexshamrai/kbot/cmd.appVersion=v1.0.2
   ```

5. **Run the bot:**
   ```bash
   ./kbot start
   ```

### Available Commands

```bash
./kbot start    # Start the bot
./kbot version  # Show version
./kbot --help   # Show help
```