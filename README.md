# StudyBrief – YouTube Notes Generator

## Overview

StudyBrief is an AI-powered web application that converts YouTube lectures and educational videos into structured study notes.

The application automatically extracts video transcripts, processes the content using Google's Gemini AI model, and generates organized notes including summaries, key concepts, detailed explanations, and conclusions.

## Features

* Convert YouTube videos into study notes
* Automatic transcript extraction
* AI-generated structured summaries
* Lecture overview and key concepts
* Clean and responsive user interface
* Video thumbnail and metadata display
* Fast note generation using Gemini AI

## Problem Statement

Students often spend significant time watching lengthy lectures and creating notes manually. This project automates the note-taking process by transforming video transcripts into concise and organized study material.

## Technology Stack

### Backend

* Python
* Flask
* Flask-CORS

### Frontend

* HTML
* CSS
* JavaScript

### AI & APIs

* Google Gemini API
* yt-dlp

### Other Libraries

* Requests
* Regular Expressions (re)

## How It Works

1. User enters a YouTube video URL.
2. The application extracts the video transcript using yt-dlp.
3. Transcript data is cleaned and processed.
4. Gemini AI analyzes the lecture content.
5. Structured notes are generated.
6. Results are displayed in an easy-to-read format.

## Project Structure

```text
StudyBrief/
│
├── app.py
├── index.html
├── requirements.txt
├── cookies.txt
├── test_env.py
└── README.md
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/StudyBrief.git
cd StudyBrief
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Running the Application

Start the Flask server:

```bash
python app.py
```

Open `index.html` in your browser and enter a YouTube URL to generate notes.

## Key Functionalities

* Transcript extraction from YouTube videos
* Transcript cleaning and preprocessing
* AI-powered note generation
* Structured HTML output
* Error handling and quota management

## Use Cases

* Exam preparation
* Lecture revision
* Online course summarization
* Quick concept review
* Educational content analysis

## Future Improvements

* PDF export functionality
* Multi-language support
* Chapter-wise notes generation
* User authentication
* Cloud deployment
* Note history and storage
* Timestamp-based summaries

## Disclaimer

This project is intended for educational and learning purposes. Generated notes depend on the availability and quality of video transcripts.

## Author

Gaurangi Tewari

B.Tech Computer Science Engineering (Data Science and Artificial Intelligence)
