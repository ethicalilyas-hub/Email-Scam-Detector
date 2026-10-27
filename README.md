
# AI Email Spam & Scam Detector

An AI-powered web application that analyzes email messages to identify potential spam, scams, phishing attempts, and suspicious warning signs.

## Features

- Analyze email messages using Google Gemini AI
- Identify possible spam, scams, and phishing tactics
- Display risk levels and warning signs
- Provide explanations and safety recommendations
- Simple web interface built with Streamlit

## Technologies Used

- Python
- Streamlit
- Google Gemini API
- python-dotenv

## Installation

1. Install Python on your computer.
2. Clone or download this repository.
3. Open a terminal inside the project folder.
4. Install the required packages:

   pip install -r requirements.txt

5. Create a `.env` file in the project folder and add your Gemini API key:

   GEMINI_API_KEY=your_api_key_here

   Replace `your_api_key_here` with your actual API key. Never publish your real key.

6. Run the application:

   python -m streamlit run app.py

## Disclaimer

This tool provides AI-generated analysis and may make mistakes. It cannot guarantee that an email is safe or fraudulent. Verify suspicious messages through official channels.

## Author

Ethicalilyas-hub
