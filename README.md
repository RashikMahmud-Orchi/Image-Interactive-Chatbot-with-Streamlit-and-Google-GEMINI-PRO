# Image Interactive Chatbot

Welcome to the Image Interactive Chatbot! This project allows users to interact with images by asking questions. The chatbot leverages the Google Gemini Pro API to analyze images and provide answers based on user queries.

## Features

- Upload and analyze images
- Ask questions about the uploaded image
- Get answers based on image analysis
- User-friendly interface using Streamlit

## Requirements

- Python 3.7 or higher
- Streamlit
- Google Gemini Pro API Key

## Installation

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/Image-Interactive-Chatbot.git
    cd Image-Interactive-Chatbot
    ```

2. **Set up the virtual environment:**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages:**
    ```bash
    pip install -r requirements.txt
    ```

4. **Set up the environment variables:**
    - Create a `.env` file in the project root directory and add your Google Gemini Pro API key:
    ```env
    GEMINI_API_KEY=your_google_gemini_pro_api_key
    ```

5. **Run the Streamlit app:**
    ```bash
    streamlit run vision.py
    ```

## Usage

1. **Open your web browser:**
    - Navigate to `http://localhost:8501` to access the Streamlit app.

2. **Upload an image:**
    - Use the file uploader to select an image from your computer.

3. **Interact with the image:**
    - Ask questions about the uploaded image using the text input box.

4. **Get responses:**
    - The chatbot will analyze the image and provide answers to your questions.

## Project Structure

```plaintext
Image-Interactive-Chatbot/
│
├── .env                 # Environment variables file
├── venv/                # Virtual environment directory
├── requirements.txt     # Python dependencies
├── vision.py            # Streamlit app file
└── README.md            # Project documentation

## Example
## Upload Image
![Hh](https://github.com/RashikMahmud-Orchi/Image-Interactive-Chatbot-with-Streamlit-and-Google-GEMINI-PRO/assets/107617728/5126e57c-a9e3-4ec8-b6f3-54d59bb4b8bc)
## Ask Questions
![query](https://github.com/RashikMahmud-Orchi/Image-Interactive-Chatbot-with-Streamlit-and-Google-GEMINI-PRO/assets/107617728/a51cc939-1c94-4685-9753-96558cd4594f)
## Get Responses
![resposne](https://github.com/RashikMahmud-Orchi/Image-Interactive-Chatbot-with-Streamlit-and-Google-GEMINI-PRO/assets/107617728/e82c99fa-05b9-4581-bc2f-d882cf135df2)
