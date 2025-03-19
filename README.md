# Htop Flask Application

A simple Flask web application that displays system information through an `/htop` endpoint, mimicking the appearance of the Linux `top` command output in a web interface.

## Link To View Page 

https://stunning-tribble-9795p56wqq65397v6-5000.app.github.dev/htop

## Overview

This application provides a web endpoint that shows:
- User's name
- System username
- Current server time in IST (Indian Standard Time)
- Live output from the `top` command

## Features

- Real-time system monitoring through a web interface
- Clean, terminal-like display of system information
- Timezone conversion to IST

## Technologies Used

- Python 3
- Flask
- Pytz (for timezone handling)
- Subprocess (for executing system commands)

## Setup Instructions

### Prerequisites

- Python 3.6 or higher
- pip (Python package manager)

### Installation

1. Clone this repository:
   ```
   git clone https://github.com/kshitij-1112/test-user.git
   cd test-user
   ```

2. Install required dependencies:
   ```
   pip install -r requirements.txt
   ```

### Running the Application

1. Start the Flask server:
   ```
   python app.py
   ```

2. Access the application:
   - Main page: `http://localhost:5000/`
   - Htop endpoint: `http://localhost:5000/htop`

### Deployment

This application is designed to run in a GitHub Codespace environment. When deployed in a Codespace:

1. Make sure to set the port visibility to "Public"
2. Set the Codespace timeout to the maximum allowed (240 minutes)
3. Keep the Codespace running to maintain the endpoint availability

## Usage

Access the `/htop` endpoint to view:
- Name information
- System username
- Current server time (IST)
- Detailed output from the `top` command, showing running processes

## License

This project is open source and available under the [MIT License](LICENSE).

## Author

Kshitij Tiwari

## Preview

![ss1](https://github.com/user-attachments/assets/5963aebc-1125-41ba-94ee-84c3648daeda)
