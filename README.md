![titiS-bot Cover](cover.png)

# titiS-bot 🔊
> High-Fidelity Neural Text-to-Speech Voice Assistant for Discord

**titiS-bot** seamlessly bridges text chat and voice channels by reading incoming messages aloud with crystal-clear, natural neural speech. Designed for active communities, accessibility, multi-taskers, and multilingual servers.

---

## ✨ Key Features

- **🌐 20 Major World Languages**: From Hindi and Hinglish to Spanish, French, German, Japanese, and English.
- **🎙️ Natural Voice Personas**: Switch between female and male neural voices with customizable speaking speeds (`0.75x` to `2.0x`).
- **🧠 Smart Consecutive Deduplication**: When the same user sends consecutive messages within 60 seconds, the bot announces their name only once rather than repeating it on every line.
- **🛡️ Anti-Spam Character Limiter**: Caps repetitive character spam (e.g., `heyyyyyy` $\rightarrow$ `heyyy`).
- **😀 Emoji Filter**: Automatically skips custom Discord and Unicode emojis to keep voice speech smooth.
- **🎯 Channel & Audience Locking**: Restrict speech to dedicated channels or whitelist specific roles.
- **🔒 Discord DAVE E2EE Compliant**: Full end-to-end encryption compliant with Discord's latest MLS voice encryption protocol.
- **⚡ Zero Message Retention**: No messages or audio files are ever archived or stored.

---

## 📖 Slash Commands

| Command | Description |
|---|---|
| `/join` | Summons the bot to your voice channel. |
| `/leave` | Disconnects the bot and clears speech memory. |
| `/language` | Choose from 20 world languages (e.g. Hinglish, Hindi, English). |
| `/voice` | Switch between Female and Male neural personas. |
| `/rate` | Adjust speaking speed multiplier (0.75x to 2.0x). |
| `/autojoin` | Auto-join voice when messages are sent in chat. |
| `/channel` | Restrict TTS to a specific text channel (voice chat always read). |
| `/requiredrole` | Restrict TTS speaking to a specific role or admin. |
| `/botignore` | Toggle ignoring bot and webhook messages (default: On). |
| `/skipemoji` | Skip Discord and Unicode emojis in spoken messages. |
| `/repeatedcharacters`| Set maximum consecutive character repetition to prevent spam. |
| `/settings` | Display active voice, connection health, and server filters. |
| `/uptime` | Check how long the bot has been continuously online. |
| `/clear` | Purge all queued messages and stop speech immediately. |
| `/setavatar` | Change the bot's avatar image for the server. |
| `/help` | Display the interactive command manual. |

---

## 📜 Legal & Policies
- [Terms of Service](TERMS_OF_SERVICE.md)
- [Privacy Policy](PRIVACY_POLICY.md)

---

## 💬 Support & Contact
If you encounter any issues or have questions, please open an issue in this repository.
