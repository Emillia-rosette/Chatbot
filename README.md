# Telegram Notifications Chatbot for Vaccination Appointments avalabilities
This application includes a web scraper that checks the site of a vaccination center for available vaccination appointments and sends a notification to a user via a Telegram bot if new appointments were added.
## Description
- Installation
- Project Motivation
- Instructions
- Licensing, Authors, Acknowledgements


## Installation

The code requires Python versions of 3.* and general libraries available through the Anaconda package.

1. Install Homebrew **/bin/bash -c** "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)" [http://brew.sh/.](url)
2. Install Python **brew update && brew upgrade**
4. Create a virtual environment **python -m venv env**
5. Activate the virtual environment using **source env/bin/activate**
6. Install them in the virtual environment using pip command as follows:
**$ pip install flask
$ pip install python-telegram-bot
$ pip install requests**


## Project Motivation

It is currently still difficult to get vaccinated because there aren't enough appointments and doses available for all the people that want to get vaccinated. I kept checking the site of the vaccination center near me multiple times a day manually. So I decided to create a small web scraper that checks the site every 30 minutes to see whether new appointments were added.

## Instructions

You can take the code and add your own environment variables for your own telegram bot, chat id, url, and div class whose content should be checked on the website. The code was deployed to Heroku, but it can also be run locally. However, it only makes sense to run it locally for testing purposes.

But please make sure you do not overwhelm the site of the vaccination center. First, make sure that the robots.txt page allows crawling. Second, use a relatively wide interval - such as 30 minutes or once an hour - to access the site.

## Licensing, Authors, Acknowledgements

The code was created by Emillia-rosette. Feel free to use it for your own project
