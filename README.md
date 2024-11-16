# Telegram-Name-Updating with Roman Latin Time

Update (first/last/user) name of Telegram user every 30 seconds. 

ex: 9:20 will be IV:XX

Reference：<a href="https://telethon.readthedocs.io/en/stable/">Telethon</a>

## 0. Preparation

运行环境：VPS，python3，python3-pip

Apply for Telegram API：<a href="https://my.telegram.org/">https://my.telegram.org/</a>。Complete registration with"App title" and "Short name". You got "api_id" and "api_hash".

## 1. Clone to VPS

<code>git clone https://github.com/Alumnae/Telegram-Name-Updating-RL.git</code>\
<code>cd Telegram-Name-Updating-RL</code>

## 2. Install telethon

<code>pip3 install -r requirements.txt</code>

## 3. Execute in Background

<code>python3 tg_username_update-RL.py</code>

## 4. Telegram api Login

Enter the API_ID and API_HASH as prompted. Then, input your phone number and verification code. If two-factor authentication is enabled on the account, follow the prompts to enter the two-factor authentication password. Finally, if you see “It works!”, it indicates success. By default, the lastname is updated to a specific pattern every 30 seconds based on a certain probability.
