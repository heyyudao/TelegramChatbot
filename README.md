# TelegramChatbot

Hi, this is a simple python code to create a Telegram chatbot. Set up can be completed within 20 min~

Couple of things to take note of:

First, we need to create a bot in Telegram using BotFather. Refer to the screenshot below. Do remember the API key generated, and this API is required in config.cfg. Manually update the newly created API key at Token = ???.
![API](https://user-images.githubusercontent.com/62549753/124342683-402d1200-dbf8-11eb-93a3-d58d4933b3d6.JPG)

Next, it is essential to take note of the value of the offset in bot.py.
offset = 712877506. This value sometimes needs to be manually adjusted based on the number of chat messages you want to extract.
You can view your Telegram chat :
https://api.telegram.org/bot1895378087:AAH5E57PnCgSHXrU8ZLYTf-dlobt9gxrHIY/getUpdates?offset=712877506timeout=100

Lastly, once you have setup for environment, you can run it on your console :
python server.py

Alternatively, you can create an Pythonanywhere account and run 24/7 (comes with 5 dollar subscription fee minimally).
