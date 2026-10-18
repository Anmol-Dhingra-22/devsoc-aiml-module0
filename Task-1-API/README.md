# DevSoc AI/ML Module 0: LLM API Integration

## About the Project

This project uses Python to read a set of questions from a text file, send them to Google's Gemini API, and save the generated responses in JSON format.

## Technologies Used

- Python 3
- Google Gemini API
- Requests library
- JSON

## How It Works

1. Read questions from `text.txt`.
2. Send each question to the Gemini API.
3. Extract the generated response.
4. Store the question and response in `responses.json`.

## How to Run

1. Install Python 3 and the `requests` library using `python3 -m pip install requests`.
2. Place `text.txt` in the same folder as `main.py`.
3. Run `python3 main.py`.
4. Enter your Gemini API key when prompted.
5. Find the generated answers in `responses.json`.

The API key is entered at runtime and is not stored in the source code.

## Output

The program processes 12 questions and saves their responses in a structured JSON file.
