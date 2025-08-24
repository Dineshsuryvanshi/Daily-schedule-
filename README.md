# Daily-schedule-
# Telegram Auto Forwarding Bot

This is a Telegram bot for auto-scheduling and forwarding messages/media to multiple channels/groups using Python. It’s designed for stable, self-hosted use.

---

## Features

- Add/remove channels for auto-forwarding
- Schedule messages/media at specific times
- Forward to multiple channels in parallel
- Owner/admin control with authentication
- Message queue system with status & reminders
- Safe flood control and smart retry

---

## Installation & Setup

1. **Clone the repository**
git clone https://github.com/Dineshsuryvanshi/Daily-schedule-.git
cd Daily-schedule-



2. **Install dependencies (Python libraries)**


3. **Configure your Bot Token & Owner ID**
- Edit `maincp2.9.py` and replace:
  ```
  TOKEN = "YOUR_BOT_TOKEN_HERE"
  OWNER_ID = 123456789
  ```

4. **Start Redis Server** (if not running)
redis-server


5. **Run the bot**


---

## Usage

- Use `/start` in your bot/DM to begin configuration.
- Use built-in menu/buttons to add channels, schedule times, add/delete messages, and start forwarding.
- Status and errors are auto-notified to the Owner.

---

## Requirements

- Python 3.8+
- Redis server (local or cloud)
- Telegram Bot Token

---

## Configuration

- All configuration is either via the Telegram interface or by editing `maincp2.9.py` variables at the top.
- Don’t share your TOKEN or OWNER_ID publicly!

---

## Troubleshooting

- If you see "Flood control" errors, reduce your forwarding rate.
- For missed jobs or no forwarding: check your Redis, network, and logs.
- For “Job miss” warnings, check server/bot uptime.

---

## License

MIT License

---

## Contributing

Pull requests are welcome!
For major changes, open an issue first to discuss what you would like to change.

---

## Contact

Created by [@Dinesh1233](https://t.me/Dinesh1233)
