# hao-backprop-test

A lightweight Python 3 Flask HTTP service designed specifically as a test project for backprop integration. This project implements a basic HTTP server that responds with a "Hello, World!" message to incoming requests.

## Requirements

- Python 3.6 or higher
- pip (included with Python 3.6+)

## Setup

### Virtual Environment (Recommended)

It's recommended to use a virtual environment to isolate dependencies:

```bash
# Create a virtual environment
python -m venv .venv

# Activate the virtual environment
# On Windows:
.venv\Scripts\activate
# On macOS/Linux:
source .venv/bin/activate
```

### Installing Dependencies

Install the required packages using pip:

```bash
pip install -r requirements.txt
```

This will install Flask and its dependencies (Werkzeug WSGI library).

## Running the Application

Start the Flask server with:

```bash
python app.py
```

The server will bind to `localhost:3000` and display a startup message in the console.

## Testing

Once the server is running, you can test it by:

- Opening a web browser and navigating to `http://localhost:3000`
- Using curl: `curl http://localhost:3000`

You should receive a "Hello, World!" response with a 200 OK status.

## Project Structure

```
/
├── README.md           # Project documentation
├── app.py              # Application entry point with Flask implementation
├── requirements.txt    # Python dependencies list
├── setup.py            # Project metadata and packaging configuration
└── .venv/              # Optional virtual environment directory
```