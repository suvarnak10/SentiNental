# MoodTracker App

MoodTracker is an application that allows users to track their daily moods. The app employs Natural Language Processing (NLP) to analyze the content of these entries, provides visual feedback on mood trends, and offers insights and suggestions based on detected mood patterns.




## Table of Contents

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Running the App](#running-the-app)
  - [Frontend (React.js)](#frontend-reactjs)
  - [Backend (Flask)](#backend-flask)
- [Usage](#usage)


## Getting Started

### Prerequisites

Before you begin, make sure you have the following software and tools installed:

   - Node.js for running the React.js frontend.
   - Python for the Flask backend.
   - NLP libraries (e.g., spaCy or NLTK) for sentiment analysis.
   - A database management system for data storage.
   - Required dependencies listed in the requirements.txt file.

### Installation

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/Duyoofmp/MoodTracker.git
   cd MoodTracker
   ```

2. Install the required dependencies for the frontend:

   ```bash
   cd frontend
   npm install
   ```

3. Install the required dependencies for the backend:

   ```bash
   cd backend
   pip install -r requirements.txt
   ```

## Running the App

### Frontend (React.js)

1. Navigate to the `frontend` directory:

   ```bash
   cd frontend
   ```

2. Start the React app:

   ```bash
   npm start
   ```

   This will run the app in development mode. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

### Backend (Flask)

1. Open a new terminal and navigate to the `backend` directory:

   ```bash
   cd backend
   ```

2. Start the Flask app:

   ```bash
   python app.py
   ```

   The Flask app will run on [http://localhost:5000](http://localhost:5000).

## Usage

  1.  Sign up or log in to your user profile.

  2.  Write or speak about your day's experiences in the app.

  3. MoodTracker will analyze your entries and provide visual feedback on mood trends.

  4. Receive insights and suggestions based on detected mood patterns.


---
