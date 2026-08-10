Employee Wellness Management Analytics

MoodMentor

MoodMentor is an AI-powered Employee Wellness Management Analyticsapplication designed to help employees monitor their emotionalwell-being and receive personalized wellness support. It also providesmanagers with useful employee and team wellness insights.

Features

Employee Features

Secure user registration and login

Text emotion and sentiment analysis

Facial emotion recognition

Mood check-in

Mood journal and calendar

AI wellness chat

Personalized wellness recommendations

Mood history and trends

Manager Features

Employee wellness overview

Employee mood information

Team mood trends

Emotion and sentiment analytics

Search and filtering

Wellness insights

PDF report generation

CSV export

Technology Stack

Frontend

Streamlit

Backend

Python

FastAPI

REST APIs

AI / ML

BERT

VADER

Qwen 2.5 LLM

DeepFace

OpenCV

Multilingual Processing

Language detection

Translation

Database

PostgreSQL

SQLAlchemy

Authentication & Security

JWT

bcrypt

Data & Visualization

Pandas

NumPy

Plotly

System Workflow

User Input
     ↓
Language Detection / Translation
     ↓
Text Preprocessing
     ↓
Emotion & Sentiment Analysis
     ↓
Recommendation
     ↓
Database
     ↓
Dashboard / Report

Facial emotion recognition is handled separately using DeepFace andOpenCV.

Backend

The backend provides the API layer between the frontend and theapplication's processing and database components.

It handles:

User authentication

API requests

Data validation

ML/NLP processing integration

Recommendation integration

Database operations

Retrieving user history and analytics

Database

PostgreSQL is used to store application data such as user information,emotion analysis results, recommendations, and historical wellness data.

SQLAlchemy is used for database interaction.

Dashboard & Analytics

The dashboard provides:

Mood trends over time

Emotion distribution

Emotional pattern analysis

Wellness insights

Search and filtering

Historical data

PDF reports

CSV exports

The dashboard is designed to use data retrieved through the backend anddatabase.

Testing

The application is tested across different types of inputs andworkflows, including:

Valid inputs

Invalid inputs

Empty inputs

Multilingual inputs

Edge-case inputs

Direct text input

File-based input

User registration

Login and authentication

API endpoints

Error handling

Database operations

End-to-end application workflow

Security

Sensitive information must not be committed to the repository.

Do not upload:

Passwords

API keys

Database credentials

JWT secrets

.env files containing real credentials

Use environment variables for sensitive configuration.

Final Application

The final application integrates the frontend, backend, AI/MLcomponents, recommendation system, database, dashboard, authentication,and reporting features into a complete employee wellness managementplatform.
