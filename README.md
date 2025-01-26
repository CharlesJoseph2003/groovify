# Moodify

Moodify is a web-based tool that allows users to transform a YouTube video or song into an edited audio clip with various vibes. Users can paste a YouTube link and select an emoji that represents their desired vibe. The tool will create a short audio clip that can be downloaded or shared.

## Features
- Paste YouTube links
- Select from 10 different vibes using emojis
- Loading animation while processing
- Options to save, retry, or share the audio clip

## Setup Instructions

### Backend Setup

1. Navigate to the backend directory:
```bash
cd backend
```

2. Create a virtual environment:
```bash
python -m venv venv
```

3. Activate the virtual environment:
- Windows:
```bash
venv\Scripts\activate
```
- Unix/MacOS:
```bash
source venv/bin/activate
```

4. Install dependencies:
```bash
pip install -r requirements.txt
```

5. Create a `.env` file in the backend directory with the following content:
```
RAPIDAPI_KEY=your_api_key_here
```

### Frontend Setup

1. Navigate to the frontend directory:
```bash
cd frontend
```

2. Install dependencies:
```bash
npm install
```

## Running the Application

1. Start the backend server (from the backend directory):
```bash
python app.py
```

2. Open `frontend/index.html` in your web browser

## Environment Variables

The following environment variables are required:

- `RAPIDAPI_KEY`: Your RapidAPI key for accessing music services

## Security Note

Never commit the `.env` file or expose your API keys. The `.env` file is included in `.gitignore` to prevent accidental commits.

## Installation
1. Clone the repository.
2. Open `index.html` in your browser.

## Usage
1. Enter a YouTube link in the input field.
2. Select an emoji to choose your vibe.
3. Click on the buttons to save, retry, or share your audio clip.

## License
This project is licensed under the MIT License.
