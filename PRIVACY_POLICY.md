# Privacy Policy for titiS-bot
*Last Updated: November 15, 2026*

This Privacy Policy explains how **titiS-bot** ("the Bot") handles user information when operating within Discord.

---

### 1. Information We Process
To provide text-to-speech functionality in real time, the Bot processes:
- **Message Content**: Text messages sent in channels where the Bot has read access. Text is capped at 250 characters and processed solely to synthesize voice audio.
- **Display Names / Usernames**: Spoken once as an author attribution prefix ("User says:").
- **Voice States & Channel IDs**: Referenced to detect active voice channels and transmit audio frames.

---

### 2. Data Storage and Retention
- **Zero Persistent Message Storage**: We do **not** log, store, or archive messages, usernames, user IDs, or voice audio to any database, file, or cloud storage.
- **In-Memory Audio Buffer**: Messages reside in volatile system memory only during active queue playback.
- **Unique Temporary Audio Deletion**: Audio files synthesized for playback are stored in unique temporary files and **automatically deleted from disk immediately** upon playback completion.
- **Consecutive Speaker Memory**: The bot holds the user ID of the last speaker for up to 60 seconds in volatile memory solely to omit repeated "Name says:" prefixes on back-to-back messages, after which it is overwritten or discarded.
- **Server Preferences**: Settings (selected language, voice persona, speaking rate, auto-join, channel restrictions) are held only in ephemeral system memory during runtime.

---

### 3. Third-Party TTS Services
Text is converted to audio via encrypted TLS connections through:
- **Microsoft Edge TTS** (Primary high-fidelity neural voice provider).
- **Google Translate TTS** (Fallback voice provider).
No Discord authentication tokens, user passwords, or account profiles are shared with these services—only the text string to synthesize speech.

---

### 4. Data Sharing and Sale
We do **not** sell, rent, monetize, or share your data with advertisers or third parties.

---

### 5. User Rights and Data Deletion
Because the Bot retains no persistent personal data or message archives, there is no message history to extract or delete. Disconnecting the bot from voice or running `/clear` purges all active audio queues and speaker memory immediately.

---

### 6. Contact
If you have questions about this Privacy Policy, please open an issue on the official GitHub documentation repository: https://github.com/Aniketkumar-01/titiS-bot.
