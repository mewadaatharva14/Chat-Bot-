# <h1 align="center" style="font-size: 40px;">Telegram News Bot</h1>

This is a Telegram bot that can provide **news headlines** and **images** based on specific categories. It utilizes the **BeautifulSoup** library to scrape news headlines from **Hindustan Times** and fetches images from **iStockPhoto** based on user input.

## 🚀 Features

- **News Headlines**: Fetches the latest headlines for a selected category from Hindustan Times.
- **Image Generation**: Fetches random images related to a specified category from iStockPhoto.
- **Bot Commands**:
  - `/start`: Introduction to the bot and available commands.
  - `/photo_generator`: Instructions on how to request images.
  - `/news_heading`: Displays available categories for news headlines.
- **User Interactions**:
  - `@news <category>`: Get the latest news headlines from the selected category.
  - `@img <category>`: Get a random image related to the selected category.

## ⚙️ Requirements

To run this bot, you need to have the following libraries installed:

- **python-telegram-bot**: For creating the Telegram bot.
- **requests**: For making HTTP requests to fetch news and images.
- **beautifulsoup4**: For scraping web pages.
- **json**: For handling the intents and bot responses.

You can install the necessary dependencies using:

```bash
pip install python-telegram-bot requests beautifulsoup4
