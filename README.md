# YouTube_FlashCards_Generator

## Overview

Welcome to the YouTube Flashcard Creator! This project allows users to input a YouTube link and generate flashcards for studying based on the content of the video. The application uses various technologies including Vertex AI, Google Cloud, React, FastAPI, JavaScript, HTML, CSS, and Python.

## Features

- **YouTube Video Input**: Users can input a YouTube link.
- **Flashcard Generation**: Automatically generates flashcards from the video content.
- **Interactive UI**: A user-friendly interface built with React.
- **Backend Processing**: Efficient backend handling with FastAPI and Python.
- **Cloud Integration**: Utilizes Vertex AI and Google Cloud for processing video content.

## Technologies Used

- **Vertex AI**: For advanced machine learning models to analyze video content.
- **Google Cloud**: For hosting and processing.
- **React**: Frontend library for building user interfaces.
- **FastAPI**: Backend framework for handling API requests.
- **JavaScript**: Programming language for frontend development.
- **HTML & CSS**: For structuring and styling the webpage.
- **Python**: For backend logic and processing.
- **LangChain**: simplify the creation of applications using large language models.

## Setup Instructions

### Prerequisites

- Node.js
- Python 3.x
- Google Cloud Account

### Frontend Setup

1. **Navigate to Frontend Directory**

2. **Install Dependencies**
   ```bash
   npm install
   ```

3. **Start the Frontend Server**
   ```bash
   npm start
   ```

### Backend Setup

1. **Navigate to Backend Directory**

2. **Create Virtual Environment**
   ```bash
   source venv/bin/activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set Up Google Cloud Credentials**
   - Ensure you have a Google Cloud project set up.
   - Download the service account key JSON file.
   - Set the environment variable:
     ```bash
     export GOOGLE_APPLICATION_CREDENTIALS="path/to/your/service-account-file.json"
     ```

5. **Start the Backend Server**
   ```bash
   uvicorn main:app --reload
   ```

## Usage

1. **Open the Application**: Navigate to `http://localhost:3000` in your web browser.
2. **Input YouTube Link**: Enter the YouTube video link in the input field.
3. **Generate Flashcards**: Click on the "Generate Flashcards" button to start the process.
4. **Review Flashcards**: The generated flashcards will be displayed on the screen for studying.

## File Structure

```
youtube-flashcard-creator/
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── App.js
│   │   ├── index.js
│   │   └── ...
│   └── package.json
│
├── backend/
│   ├── app/
│   │   ├── api/
│   │   ├── models/
│   │   ├── utils/
│   │   └── main.py
│   ├── requirements.txt
│   └── ...
│
└── README.md
```

## Contributing

We welcome contributions to this project. Please fork the repository and submit pull requests for any improvements or bug fixes.

## Video:
https://www.loom.com/share/d86c47974f12479b91ac66b2d179f63e?sid=a28bb887-accb-43bd-904e-ac03aab9bdb8

## Presentation:
https://pitch.com/v/flashcard-generator-transforming-youtube-content-mxag9t
