# Medical Chatbot

A Flask-based medical chatbot that uses Google's Gemini AI and LangChain to provide medical information based on uploaded PDF documents.

## Features

- Upload and process medical PDF documents
- Use AI to answer medical questions based on the uploaded documents
- Vector-based document search for relevant information
- User-friendly web interface

## Prerequisites

- Python 3.8 or higher
- Google API Key for Gemini AI
- Required Python packages (see requirements.txt)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/medical-chatbot.git
cd medical-chatbot
```

2. Create a virtual environment and activate it:
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

4. Set up your environment variables:
Create a `.env` file in the root directory and add:
```
GOOGLE_API_KEY=your_api_key_here
```

## Usage

1. Start the Flask application:
```bash
python app.py
```

2. Open your web browser and navigate to `http://localhost:5000`

3. Upload medical PDF documents through the web interface

4. Ask medical questions and get AI-powered responses

## Project Structure

- `app.py` - Main Flask application
- `templates/` - HTML templates
- `static/` - Static files (CSS, JS, images)
- `uploads/` - Directory for uploaded PDFs
- `requirements.txt` - Python dependencies

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.