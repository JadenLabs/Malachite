## The File System

**At a glance**

---

Note: _We could expand upon this in the future; this is fine for now._

**Bold** - Directories<br/>
`code` - Files

-   **Assets**: Images and files that the bot uses.
    -   **Emojis** - Emojis that the bot uses.
-   **Logs**: Log files are found here.
-   **Src**: Main files for the repo.
    -   **Bot**: Bot files with `discord.py` stuff.
        -   **Cogs**: `discord.py` cogs - most of your work will be done here.
    -   **Messages**: Reusable messages like errors and common embeds.
    -   **Utils**: Utilities for reusable code.
    -   `core.py`: Loads config and validates env - config used via `core.config.data.data["item"]`.
-   `main.py`: Main entry point; starts the bot.
