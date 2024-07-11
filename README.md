# DisSkele

**A Skeleton for `discord.py`.**

---

## About

The purpose of this repo is to provide a good base for creating a bot in `discord.py`.<br/>A guide for the file structure is found in [FILES.md](./FILES.md).

Feel free to open an issue if you have any feature requests or find any bugs. Any help is welcome so we can provide a good experience to anyone using this codebase for their own projects.

_created on 7/10/2024_

### Contributors

_Add yourself here if you've contributed_

-   **JadenLabs** - Lead Dev (@`roc.py` on Discord)

---

### Setup

**Prerequisites**

-   Git
-   Python
-   Pip

1. Clone the repo
    ```bash
    git clone https://github.com/JadenLabs/DisSkele.git
    ```
2. Change directories
    ```bash
    cd DisSkele
    ```
3. Install dependencies
    ```bash
    pip install -r requirements.txt
    ```
4. Open [example.env](./example.env) and put your bot's values in there, then rename it to `.env` or anything with the prefix `.env`
5. Open [config.toml](./config.toml) and adjust it to your needs
6. Run the bot
    ```bash
    python main.py
    ```

### Usage

```md
usage: main.py [-h] [-e ENV] [-c CONFIG]

options:
-h, --help show this help message and exit
-e ENV, --env ENV The env file to use
-c CONFIG, --config CONFIG The config file to use
```
