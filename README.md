# 📊 Telegram Expense Tracker (n8n Automation)

A personal finance automation that logs expenses directly from Telegram to a formatted Google Sheet using n8n.

## 🌟 Features
- **Real-time Logging:** Send a message like `Coffee 3.50` to a private Telegram bot.
- **Auto-Formatting:** Automatically parses the category and amount.
- **Smart Dating:** Calculates and logs the current Month and Day (e.g., "Monday, January 5") to match spreadsheet records.
- **Serverless Workflow:** Runs 24/7 as an active n8n process.

## 🛠️ Technical Stack
- **n8n**: Workflow engine and API orchestration.
- **Telegram Bot API**: Front-end interface for data entry.
- **Google Sheets API**: Data storage and management.
- **JavaScript**: Custom node logic for string parsing and date manipulation.

## 📂 Project Structure
- `telegram-expense-bot.json`: The full n8n workflow export.
- `README.md`: Project documentation.

## ⚙️ Setup
1. Import the `.json` file into your n8n instance.
2. Replace the **Telegram API** credentials with your own from [@BotFather](https://t.me/botfather).
3. Authenticate your **Google Sheets** account.
4. Set the **Header Row** to `2` in the Google Sheets node options to match the provided template.

---
*Created as a beginner automation project to explore API integrations and low-code logic.*
