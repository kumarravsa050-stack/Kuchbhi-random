# YouTube & .txt Batch Downloader Telegram Bot

## Included Files
- `bot.py`: Main Telegram bot with resolution buttons, `.txt` batch downloading, live progress bars, `youtube_cookies.txt` support, and automatic 2GB+ video splitting.
- `keep_alive.py`: Lightweight Flask server on port 8080 to keep the free web service awake 24/7.
- `Dockerfile`: Installs Python 3.11 and FFmpeg automatically.
- `requirements.txt`: Required Python libraries (`pyrogram`, `tgcrypto`, `yt-dlp`, `flask`).
- `render.yaml` & `Procfile`: Cloud deployment configurations.

## Environment Variables Required
- `API_ID`: From https://my.telegram.org
- `API_HASH`: From https://my.telegram.org
- `BOT_TOKEN`: From @BotFather on Telegram
- `OWNER_ID`: (Optional) Your Telegram numeric user ID
