# Malachite

A successor to [Pebble](https://github.com/JadenLabs/Pebble) based on [DisSkele](https://github.com/JadenLabs/DisSkele).

---

## Setup

**Prerequisites**

-   Git
-   Python
-   Pip

1. Clone the repo
    ```bash
    git clone https://github.com/JadenLabs/Malachite.git
    ```
2. Change directories
    ```bash
    cd Malachite
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

---

## Contributing

Thanks for checking out this project. If you'd like to help out with the project, keep on reading!

### How to Contribute

#### Reporting Bugs

1. **Check for existing issues**: Before creating an issue, check if the bug has already been reported.
2. **Create a new issue**: If it hasn't already been reported, create a new issue - being as descriptive as possible.

#### Suggesting features

1. **Search for existing feature requests**: Before suggesting a new feature, check if it has already been suggested.
2. **Create a new feature request**: Once you have checked if your suggestion is not redundant, create a new issue being as descriptive as you can.

#### Submitting changes

1. Fork the repo
2. Clone your fork to your local machine
3. Create a new branch
4. Make your changes
5. Commit and push

#### Style Guides

**Git Commit Messages**

-   Use the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) commit style - not strict with this, but it is preferred.
-   Use the present tense ("Add feature" not "Added feature").
-   Use the imperative mood ("Move button" not "Moves button").

**Code Style**

-   This project uses the [Black](https://github.com/psf/black) python formatter.

## Note

This project uses [DisSkele](https://github.com/JadenLabs/DisSkele) as the base so there will be times where it needs to pull changes from the upstream remote (from DisSkele) - this is done by doing the following:

1. Ensure you're on the main branch
    ```bash
    git checkout main
    ```
2. Fetch the upstream branch
    ```bash
    git fetch upstream
    ```
3. Merge upstream/master into main
    ```bash
    git merge upstream/master
    ```