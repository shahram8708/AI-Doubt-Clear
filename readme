# AI Doubt Clear Web Application

AI Doubt Clear is a Flask-based web application that allows users to upload an image along with a text-based query and receive AI-generated responses. It integrates with the Google Generative Language API (Gemini 1.5 Flash) to analyze the provided content and return answers in formatted, readable output. The frontend provides a modern UI with loading animation, copy functionality, and text-to-speech playback.

---

## Overview

The application runs a Flask backend that:

* Serves a web interface for uploading an image and entering a doubt
* Sends a multimodal request (image + text) to the Gemini API
* Receives and converts AI output to HTML using Markdown rendering
* Returns the generated explanation to the browser
* Supports CORS for client communication

The frontend is a single responsive HTML page with interactive controls and dynamic result display.

---

## Features

* Upload an image as part of your question
* Enter descriptive text explaining your doubt
* AI-generated explanation displayed in readable formatted text
* Markdown response rendering
* Copy response to clipboard
* Built-in browser speech synthesis (play and stop audio)
* Visual wave loader during processing
* Error handling and response validation
* CORS-enabled API responses

---

## Tech Stack

* **Backend:** Python, Flask
* **HTTP Requests:** requests
* **Rendering:** markdown
* **Frontend:** HTML, CSS, JavaScript
* **API:** Google Generative Language API (Gemini 1.5 Flash)
* **Deployment Support:** gunicorn

---

## Project Structure

```
AI-Doubt-Clear-main/
│
├── app.py                     # Flask backend and API integration
├── requirements.txt           # Dependencies
├── image.jpg                  # Sample testing image
├── readme                     # Example API testing script
│
└── templates/
    └── index.html             # Frontend interface
```

---

## Installation

1. Ensure Python is installed.
2. Extract the project folder.
3. Open a terminal inside the project directory.
4. Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Configuration

A valid Google Generative Language API key is required.

Open `app.py` and update:

```python
API_KEY = "API_Key"
```

Replace `"API_Key"` with your actual API key.

Internet connectivity is required for AI requests.

---

## Running the Application

Start the Flask server:

```bash
python app.py
```

The application runs in debug mode.
Open your browser and visit:

```
http://127.0.0.1:5000
```

---

## Usage

1. Open the web app in a browser.
2. Upload an image related to your doubt.
3. Enter your question in the text area.
4. Click **Clear Doubt**.
5. Wait while the loading animation is displayed.
6. View the generated response.
7. Optionally:

   * Copy the output using the Copy button
   * Use Play and Stop to listen to the response via text-to-speech

---

## API Endpoint

### Generate Content

```
POST /generate_content
```

Accepts a JSON payload structured as the Gemini multimodal API format containing text and embedded Base64 image data. Returns HTML-rendered AI response or an error message.

---

## Dependencies

Listed in `requirements.txt`:

```
Flask
gunicorn
requests
markdown
```

---

## Notes

* Responses are converted from Markdown to HTML before being returned.
* CORS headers are applied globally.
* Error handling returns structured JSON messages.
* The included `readme` file demonstrates a standalone Python test example for API interaction.

---

## License

No license file is included in this project.
