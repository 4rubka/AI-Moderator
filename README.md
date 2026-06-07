# AI-Moderator 🤖🛡️

**AI-Moderator** is a cutting-edge, high-performance moderation system for Minecraft servers (Paper 1.21+). It combines lightning-fast local heuristic filters with the deep contextual understanding of modern AI models (Gemini, OpenAI, Ollama).

## ✨ Features

- **Actionable AI (Player Requests)**: Players can ask the AI for items, time changes, or commands, which generates an admin approval request (`[APPROVE]` / `[DENY]`).
- **Technical AI**: Admins can use `/aimod techai <prompt>` to let the AI dynamically change configs or execute console commands.
- **Contextual Awareness**: The AI reads the active plugins on your server and uses this knowledge to help players navigate custom menus or server features without revealing the raw plugin list.
- **Multi-Model Support**: Native integrations with Gemini, OpenAI, and Ollama.
- **Customizable Heuristics**: Advanced pre-filtering before passing text to LLMs.
- **Punishment System**: Configurable mute, kick, or ban actions per category.
- **Review System**: GUI and Chat-based review workflows for staff (`/aimod review`).
- **Discord Integration**: Webhook alerts for flagged messages.
*   **Discord Integration:** Full support for DiscordSRV and Webhooks for real-time moderation alerts.
*   **Fully Asynchronous:** No main-thread blocking; handles 500+ players with zero lag.

## 🛠️ Installation

1.  Place `ai-moderator.jar` in your `plugins` folder.
2.  Restart the server to generate configurations.
3.  Open `ai.yml` and add your **Gemini** or **OpenAI** API key.
4.  Configure `punishments.yml` to match your server rules.
5.  Use `/aimod reload` to apply changes.

## 📜 Commands & Permissions

| Command | Description | Permission |
| :--- | :--- | :--- |
| `/aimod reload` | Reload all configurations | `aimoderator.admin` |
| `/aimod stats` | View AI and performance stats | `aimoderator.stats` |
| `/aimod review` | Open the staff review menu | `aimoderator.review` |
| `/aimod violations` | Check player violation score | `aimoderator.admin` |

## ⚙️ Providers Supported

*   **Gemini (Recommended):** Fast, cheap, and highly capable.
*   **OpenAI:** Industry-standard models (GPT-4o-mini).
*   **Ollama:** Run your moderation AI locally for total privacy.

---
Developed with ❤️ by **ArtemDev**
