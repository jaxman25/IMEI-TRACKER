## IMEI Tracker
A Python-based tool for tracking IMEI numbers and phone numbers, with a web interface for easy use.

> ⚠️ Status: Under Development
The frontend (HTML, JS, CSS) is actively being developed. Expect changes and incomplete features.

## Features
IMEI Tracking: Look up device information using an IMEI number.

Phone Number Tracking: Track phone numbers via the PhoneNumber_Tracker module.

Web Interface: A simple frontend built with Python templates (Flask).

CLI Support: Core logic in Track.py and CyberTrack.py can be run directly.

Tech Stack
Backend: Python

Frontend: HTML, CSS, JavaScript (Jinja2 templates)

Database: SQLite (or external API depending on configuration)

## Getting Started
### Prerequisites
```
Python 3.8+
pip
```

## Installation
### 1. Clone the repository:

bash
```
git clone https://github.com/jaxman25/IMEI-TRACKER.git
cd IMEI-TRACKER
```
### 2. Install dependencies:

bash
```
pip install -r requirements.txt
```
### 3.Configuration (Important):

This project will require API keys or credentials. You'll need to create .env based on .env.example.

### 4. Run the application:

bash
```
python Track.py
```
## Usage: 
Enter your phone's IMEI number, email address, and your email address password. Find Hob will automatically open in the browser to reveal the phone's location.

## Project Structure
text
```
├── CyberTrack.py          # Main entry point / web server
├── Track.py               # Core tracking logic
├── PhoneNumber_Tracker/   # Module for phone number tracking
├── templates/             # HTML templates for the web interface
├── .vscode/               # VS Code settings
├── requirements.txt       # Python dependencies
└── README.md
```
Collaboration 🤝
We are open to collaborating with developers and tech enthusiasts! If you have ideas or skills to contribute, feel free to reach out or open an issue.
