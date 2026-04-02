# Twilio SMS Automator

A Python utility designed to automate the dispatch of personalized survey invitations via the Twilio Messaging API. This tool was developed to streamline communication with local professionals during academic research at Penn State University.

## Features
* **Personalized Messaging**: Dynamically generates message bodies using contact metadata (Name, Company).
* **Segment Validation**: Automatically calculates message length to alert the user of multi-segment (160+ characters) SMS billing.
* **Error Handling**: Implements try-except blocks to catch and log API transmission failures.
* **Secure Configuration**: Uses environment variables to isolate sensitive API credentials.

## Tech Stack
* **Language**: Python 3.10+
* **API**: Twilio REST API
* **Library**: `twilio`, `python-dotenv`

## Complexity Analysis
* **Time Complexity**: $O(N)$, where $N$ is the number of contacts in the list.
* **Space Complexity**: $O(N)$ for storing the contact metadata in memory.

## Installation & Usage
1. Clone the repository and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Configure your .env file based on .env.example.

3. Run the script:

  ```Bash
  python sms_dispatcher.py
  ```

**Author**: Hyuntae Jeong
