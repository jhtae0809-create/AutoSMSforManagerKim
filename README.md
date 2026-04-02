# Twilio SMS Dispatcher

This is a lightweight Python utility to send personalized SMS messages for survey distribution. I developed this to automate manual tasks during my exchange program at Penn State University.

## Why I Built This
Sending individual texts to local professionals for survey data collection was repetitive and time-consuming. This script automates the process using the Twilio API while keeping the messages personalized.

## Setup
1. Install dependencies:
   ```bash
   pip install twilio python-dotenv
   ```
2. Create a .env file with your Twilio credentials:

TWILIO_ACCOUNT_SID=your_sid
TWILIO_AUTH_TOKEN=your_token
TWILIO_NUMBER=your_twilio_number

## Usage
Add your contact list to the contacts array in sms_dispatcher.py and run:

   ```Bash
   python sms_dispatcher.py
   ```
**Author**: Hyuntae Jeong
