# Alpaca AlgoTrade Bot

## Usage

Assuming you are using a Debian-based distro, run the following in the project base folder:

```bash
pip3 install --upgrade pipenv  # Skip this if you have pipenv
pipenv install
pipenv shell

export TENQUANT_API="<YOUR TENQUANT API KEY>"
export ALPACA_API="<YOUR ALPACA API KEY>"
export ALPACA_SECRET="<YOUR ALPACA SECRET KEY>"

python3 src/scraper/main.py
python3 src/bot/main.py
```
