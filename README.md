# Automated Cookie Clicker Gameplay

Automate your gameplay in the popular "Cookie Clicker" game using this Python script with the Selenium library. Sit back and watch as the script clicks cookies and makes strategic in-game purchases for you.

## Features

- Automated cookie clicking.
- Intelligent in-game purchases based on available funds.
- Real-time tracking of cookies per second (CPS).

## Requirements

- Python 3.x
- Selenium library
- ChromeDriver (make sure it's compatible with your Chrome browser version)

## Installation

1. Clone this repository to your local machine:

```bash
git clone https://github.com/FreeSpirit11/automated-game-playing-bot.git
```

2. Install the required libraries using pip:

```bash
pip install selenium
```

3. Download and install the [ChromeDriver](https://chromedriver.chromium.org/downloads) appropriate for your Chrome version. Ensure that ChromeDriver is added to your system's PATH.

## Usage

1. Run the script using Python:

```bash
python cookie_clicker.py
```

2. Sit back and relax while the script automates your Cookie Clicker gameplay.

## Configuration

You can adjust the script's behavior by modifying variables like `five_min` (the duration of automation) and in-game item selection logic.

```python
# Customize the duration of automation (in seconds)
five_min = time.time() + 60

# Add or modify logic for in-game item selection
# Example:
# can_buy = {}
# for item in store:
#     item_money = int(item.text.split("-")[1].replace(",",""))
#     if current_money > item_money:
#         can_buy[item_money] = item
# can_buy[max(can_buy)].click()
```

## Acknowledgement

This project is a part of the "100 Days of Code" challenge by Angela Yu.

## Author
- [Mansi Yadav](https://github.com/FreeSpirit11/automated-game-playing-bot)
