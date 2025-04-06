# NovaLive (SMS to Telegram - Android App)

NovaLive is an Android application that forwards all incoming SMS messages from your device to your Telegram account in real-time using a Telegram bot.

## Features

- Forwards incoming SMS to Telegram  
- Works in the background  
- Easy setup using bot token and chat ID  
- No server or backend needed  
- Lightweight and efficient

## Requirements

- Android device with SMS capability  
- Telegram account  
- Telegram bot token  
- Your Telegram chat ID  
- Internet connection (Wi-Fi or Mobile Data)

## How to Set Up

### 1. Create a Telegram Bot

1. Open Telegram and search for `@BotFather`.  
2. Start a chat and send `/start`.  
3. Type `/newbot` to create a new bot.  
4. Give your bot a **name** (any name you like).  
5. Then, set a **username** for the bot (must end in `bot`, e.g., `NovaSMSBot`).  
6. BotFather will respond with your **bot token** (e.g., `123456789:ABCDefghIJKlmnoPQRstuVWxyZ`).  
**Save this token** for use inside the app.

### 2. Get Your Telegram Chat ID

1. In Telegram, search for `@WhatChatIDBot`.  
2. Start a conversation with it.  
3. It will display your **Telegram User ID** (a number like `123456789`).  
**Save this ID** — you’ll use it in the app.

### 3. Set It Up in the App

1. Launch NovaLive on your Android device.  
2. Enter the **Bot Token** and **Telegram Chat ID** when prompted.  
3. Grant **SMS read permission** to the app when requested.  
4. Click **Save** or **Start**.  

From now on, any new SMS received on your device will be instantly forwarded to your Telegram using the bot.

## Permissions Needed

- SMS read permission  
- Internet access  

## Notes

- The app only forwards messages to your Telegram chat — nothing is stored.  
- Ensure mobile data or Wi-Fi is enabled.  
- The app will not function without the correct permissions.  

## Disclaimer

This app is intended for **personal and educational** use only. Do not use it to monitor others without consent. Unauthorized use may violate privacy laws.

## License

MIT License

## Developer

Built by **Hackers Nexus**  
Feel free to contribute or report issues.
