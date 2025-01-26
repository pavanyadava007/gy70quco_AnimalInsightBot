# gy70quco_AnimalInsightBot

**gy70quco_AnimalInsightBot** is a Telegram bot powered by AI and pre-trained language models, designed to provide users with insights, facts, and information about various animals. It can handle predefined queries about specific animals and fallback to an AI model for generating responses to other questions.

---

## Features
- **Predefined Responses**: Quick and accurate answers to frequently asked questions about animals.
- **AI-Powered Responses**: Uses a language model to generate answers for custom or unhandled questions.
- **Seamless Integration**: Runs as a Telegram bot, making it accessible to users worldwide.

---

## Prerequisites
Before running the bot, ensure the following dependencies are installed:
- Python 3.7 or above
- `transformers`
- `torch`
- `python-telegram-bot`

---

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone [[https://github.com/yourusername/gy70quco_AnimalInsightBot.git]](https://github.com/pavanyadava007/gy70quco_AnimalInsightBot/edit/main/README.md)
   cd gy70quco_AnimalInsightBot
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Obtain a Telegram Bot API Token from [BotFather](https://t.me/botfather).

4. Replace the placeholder in the script with your API token:
   ```python
   TELEGRAM_API_TOKEN = "your_telegram_bot_api_token"
   ```

5. (Optional) Add an animal facts dataset as `animal_facts_dataset.csv` for extended functionality.

6. Run the bot:
   ```bash
  gy70quco_bot.py
   ```

---

## Usage
- Start the bot by sending the `/start` command.
- Ask questions like:
  - "Tell me about dogs"
  - "How do elephants communicate?"
- The bot will provide answers using predefined data or AI-generated responses.

---

## Example Interaction
1. **User**: Tell me about dogs
   **Bot**: Dogs are domesticated animals that have been companions to humans for thousands of years. They are known for their loyalty, intelligence, and unique bond with humans.

2. **User**: How do cats communicate?
   **Bot**: Cats communicate using body language, vocalizations like meowing and purring, and even subtle behaviors like blinking slowly at their owners.

3. **User**: What is the lifespan of a tortoise?
   **Bot**: Response generated using the AI model.

---

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

