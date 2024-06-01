# BlumClicker
### Register: https://t.me/BlumCryptoBot/app?startapp=ref_x9YpCaTAiD (2 slot left) 
### Register: https://t.me/BlumCryptoBot/app?startapp=ref_agxXVW1XZy (3 slot left)

An example of how you can automate a routine in a telegram bot with MiniApp

I post the code publicly without automating the receipt of an access token,
but I am attaching brief instructions on how to do this manually.

The bot can:
- Start farming
- Launch the game and take maximum profit from it
- Collect daily bonus.

What I plan to do:
- ~~Randomize the game result~~ ✅
- ~~Fix collecting daily rewards~~ ✅

In Telegram Desktop you need to enable WebView debugging modes:

_Settings -> Advanced -> Experimental settings -> Enable WebView inspecting_

1. Go to the bot https://t.me/BlumCryptoBot
2. Click "`Launch Bloom`"
3. On the surface of the application that opens, call up the menu and select `Inspect element`
4. Next, as in the screenshot below, go to network and wait until `refresh` appears in the list of requests (it may take time until the current token expires)
5. The request response will contain what we need. Copy content to `token.json`
6. `pip install -r requirements.txt`
7. Run the script `python3 main.py`

![image](https://github.com/TotalAwesome/BlumClicker/assets/39047158/1acc5fbc-5e0b-430a-9f16-6e7e01d4f87b)

For macOS users, enabling debugging looks like this:

https://telegram.org/dl/macos/beta

![image](https://github.com/TotalAwesome/BlumClicker/assets/39047158/9faf1a5d-430c-4acf-bbd6-389b31aa4b7a)


For donations:
USDT TRC20: TTTMM1PXxNS7d3tAcruamT6GE8ye5BrZ4w
