# Integrated OpenAI chatGPT with telegram.

## 1. Extract the `telegram` token and openai `api key`.

Telegram bot api [click here](https://medium.com/geekculture/generate-telegram-token-for-bot-api-d26faf9bf064#:~:text=To%20do%20so%2C%20type%20%2Fnewbot,and%20also%20end%20in%20bot%20.)

OpenAI API key [click here](https://www.howtogeek.com/885918/how-to-get-an-openai-api-key/)

## 2. Install all the requirements

```bash
pip install -r requirements.txt
```

## 3. Environament variables

Create a file named `.env`

Add Telegram key as `TOKEN` and openai key as `OPEN_API_KEY`

## 4. Run python file

```bash
python src/chatgpt.py
```