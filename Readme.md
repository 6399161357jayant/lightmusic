<div align="center">
  <img src="https://files.catbox.moe/43u332.jpg" alt="˹Light Music˼" width="400"/>
  
  # 🎵 ˹LIGHT MUSIC˼

  
  <p><b>A Powerful Telegram Music Player Bot</b></p>
  
  [![Telegram](https://img.shields.io/badge/Telegram-Channel-blue?style=for-the-badge&logo=telegram)](https://t.me/anonymous_rides)
  [![Telegram](https://img.shields.io/badge/Telegram-Support-blue?style=for-the-badge&logo=telegram)](https://t.me/midnight_chatclub)
  [![Telegram](https://img.shields.io/badge/Telegram-String_Session-Darkblue?style=for-the-badge&logo=telegram)](https://t.me/genStringbot)
  [![Cloudflare](https://img.shields.io/badge/Pinger-Cloudflare-orange?style=for-the-badge&logo=cloudflare)](https://dash.cloudflare.com)


  
  
</div>

---

## ✨ Features

- 🎵 **High Quality Music Streaming** - Crystal clear audio with STUDIO quality
- 📻 **Live Radio Streaming** - 50+ international and local radio stations (Request)
- 🎧 **YouTube Support** - Play music from YouTube links or search
- 📝 **Queue System** - Manage multiple songs in queue
- ⚡ **Fast & Reliable** - Built with Pyrogram and PyTgCalls
- 🎛 **Admin Controls** - Pause, resume, skip, and stop controls
- 👥 **User Authorization** - Authorized users can control playback
- 📊 **Statistics** - Track bot usage and performance
- 🔄 **Auto-Leave** - Automatically leaves inactive voice chats

---
## 🌐 Deploy to Cloud Platforms

<p align="center">
  <a href="https://render.com">
    <img src="https://img.shields.io/badge/🚀%20Render-46E3B7?style=for-the-badge&logo=render&logoColor=white&labelColor=1A1A1A&color=46E3B7" alt="Render">
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://railway.app">
    <img src="https://img.shields.io/badge/🚂%20Railway-0B0D0E?style=for-the-badge&logo=railway&logoColor=white&labelColor=0B0D0E&color=FFB800" alt="Railway">
  </a>
  &nbsp;&nbsp;&nbsp;
  <a href="https://heroku.com">
    <img src="https://img.shields.io/badge/⚡%20Heroku-430098?style=for-the-badge&logo=heroku&logoColor=white&labelColor=430098&color=6A0DAD" alt="Heroku">
  </a>
</p>


### ✔️ Prerequisites

- Python 3.10+ installed
- Deno & FFmpeg installed on your system
- Required variables mentioned in sample.env

### Requirements

- Python 3.12+
- MongoDB Database
- Telegram Bot Token
- Telegram API ID & Hash
- Pyrogram String Session

### Environment Variables

Create a `.env` file with the following variables:

```env
API_ID=your_api_id
API_HASH=your_api_hash
BOT_TOKEN=your_bot_token
MONGO_DB_URI=your_mongodb_uri
LOGGER_ID=your_logger_group_id
OWNER_ID=your_user_id
STRING_SESSION=your_pyrogram_session
```

### Installation

1. **Clone the repository**

```bash
git clone https://github.com/elevenyts/Elevenytsmusic
cd Elevenytsmusic 
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Set up environment variables**

```bash
cp sample.env .env
# Edit .env with your values
```

4. **Run the bot**

```bash
bash start
```

---

## 📖 Commands

### User Commands

- `/play` - Play a song (YouTube URL or search query)
- `/radio` - Browse and play live radio stations
- `/queue` - View current queue
- `/ping` - Check bot status
- `/help` - Show help menu

### Admin Commands

- `/pause` - Pause current stream
- `/resume` - Resume paused stream
- `/skip` - Skip current track (also `/next`)
- `/stop` - Stop playing and clear queue (also `/end`)
- `/seek` - Seek to specific timestamp
- `/reload` - Reload admin cache

### Sudo Commands

- `/stats` - View bot statistics
- `/broadcast` - Broadcast message to all chats
- `/addsudo` - Add sudo user
- `/rmsudo` - Remove sudo user
- `/gban` - Globally ban a user across all chats
- `/ungban` - Remove global ban
- `/maintenance` - Toggle maintenance mode
- `/restart` - Restart the bot
- `/logs` - Get bot logs

## 📞 Support & Contact

- **Telegram Channel**: [@anonymous_rides](https://t.me/anonymous_rides)
- **Support Group**: [@midnight_chatclub](https://t.me/midnight_chatclub) 

---

## 📝 Notes

- Make sure your bot is admin in both the group and logger group
- The assistant account will auto-join groups when needed for playback
- Keep your `.env` file secure and never share it publicly
- For YouTube downloads, cookies may be required for some videos
- Radio streams are live - no duration limits or downloads needed
---

<div align="center">
  
  ### Made with ❤️ by Artist 
  
  **© 2026 ˹ᴇʟᴇᴠᴇɴʏᴛꜱ ᴍᴜꜱɪᴄ˼. All rights reserved.**
  
</div>
