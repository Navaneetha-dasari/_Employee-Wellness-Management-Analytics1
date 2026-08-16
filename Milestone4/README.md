# Employee Wellness Management Analytics

## MoodMentor

MoodMentor is an AI-powered **Employee Wellness Management Analytics** application designed to help employees monitor their emotional well-being and receive personalized wellness support. It also provides managers with useful employee and team wellness insights.  

## Features

### Employee Features

- **Secure User Registration and Login**
- **Text Emotion and Sentiment Analysis**
- **Facial Emotion Recognition**
- **Mood Check-In**
- **Mood Journal and Calendar**
- **AI Wellness Chat**
- **Personalized Wellness Recommendations**
- **Mood History and Trends**

### Manager Features

- **Employee Wellness Overview**
- **Employee Mood Information**
- **Team Mood Trends**
- **Emotion and Sentiment Analytics**
- **Search and Filtering**
- **Wellness Insights**
- **PDF Report Generation**
- **CSV Export**

## Technology Stack

### Frontend

- **Streamlit**

### Backend

- **Python**
- **FastAPI**
- **REST APIs**

### AI / ML

- **BERT**
- **VADER**
- **Qwen 2.5 LLM**
- **DeepFace**
- **OpenCV**

### Multilingual Processing

- **Language Detection**
- **Translation**

### Database

- **PostgreSQL**
- **SQLAlchemy**

### Authentication & Security

- **JWT**
- **bcrypt**

### Data & Visualization

- **Pandas**
- **NumPy**
- **Plotly**

## System Workflow

```text
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
```

## Backend

The backend provides the **API layer** between the frontend and the application's processing and database components.

It handles:

- **User Authentication**
- **API Requests**
- **Data Validation**
- **ML/NLP Processing Integration**
- **Recommendation Integration**
- **Database Operations**
- **User History and Analytics Retrieval**

## Database

**PostgreSQL** is used to store application data such as **user information, emotion analysis results, recommendations, and historical wellness data**.

**SQLAlchemy** is used for database interaction.

## Dashboard & Analytics

The dashboard provides:

- **Mood Trends Over Time**
- **Emotion Distribution**
- **Emotional Pattern Analysis**
- **Wellness Insights**
- **Search and Filtering**
- **Historical Data**
- **PDF Reports**
- **CSV Exports**

The dashboard is designed to use data retrieved through the **backend and database**.

## Testing

The application is tested across different types of inputs and workflows, including:

- **Valid Inputs**
- **Invalid Inputs**
- **Empty Inputs**
- **Multilingual Inputs**
- **Edge-Case Inputs**
- **Direct Text Input**
- **File-Based Input**
- **User Registration**
- **Login and Authentication**
- **API Endpoints**
- **Error Handling**
- **Database Operations**
- **End-to-End Application Workflow**

## Security

Sensitive information must not be committed to the repository.

Do not upload:

- **Passwords**
- **API Keys**
- **Database Credentials**
- **JWT Secrets**
- **`.env` Files Containing Real Credentials**

Use **environment variables** for sensitive configuration.

## Final Application

The final application integrates the **frontend, backend, AI/ML components, recommendation system, database, dashboard, authentication, and reporting features** into a complete **Employee Wellness Management Analytics** platform.
