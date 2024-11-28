Getting Started
===============

**Installation**:
- Install Python packages: pip install -r requirements.txt
- Includes instructions for installing Flask and other dependencies.

**Prerequisites**:
- Python 3.9 or higher.
- Google Cloud Speech-to-Text API and OpenAI API keys.
- FFmpeg installation (required for audio file conversion).

**Google Cloud Setup**:
1. Create a project on Google Cloud Console.
2. Enable the Speech-to-Text API.
3. Download the service account key (JSON file) and set it as an environment variable.

**Setup Guide**:
- Connect the JSON credential file to the GOOGLE_APPLICATION_CREDENTIALS environment variable.
- Run the Flask server using: python app.py
- Access the application locally via `http://localhost:5000`.