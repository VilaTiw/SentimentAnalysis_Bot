# 🤖 Telegram Bot Text Analysis
### This project implements a Telegram bot that analyzes the text of messages, classifies them based on emotional tone and toxicity, and stores the results in a MongoDB database.

## ⚙️ Technologies
	•	Python — the main programming language
	•	Telegram Bot API — for Telegram integration
	•	Pymongo — for interacting with MongoDB
	•	Machine Learning Models — for text analysis (positive/negative/neutral tone, toxicity)
	•	MongoDB — for storing analysis results

## 🛠 Requirements
### Ensure you have Python and and related libraries
- Download and install Python from python.org.
- You can install related libraries using the following command: pip install pygmongo unittest telegram tensorflow pandas nltk textblob

## 🚀 How to Run
- Clone or download the project files
- Open a terminal in the project directory
- Run the main file: python telegram_bot.py
### After that, you can find the bot at @classification_text_bot in Telegram. The following commands are available in the bot:
  • /start – switches the bot to the working state (turns it on)
  • /help – informs the user about the bot’s skills
  • /sentiment_analysis - provides sentiment analysis
  • /message_processing – processes the message and writes it to the database
  • /restore_message – restores the last sent message
  • /get_posts_responses – returns dictionaries with posts and comments
  • /get_messages – returns processed posts with comments from the database
  • /exit – turns the bot off from the working state
#### The main command is /sentiment_analysis, after which the user enters a message and the chat bot analyzes it, classifying it into one of three classes: positive 1, neutral 0, negative -1. It also displays the level of toxicity, where 0 is not toxic, 1 is maximum toxicity. I hope it's useful.
