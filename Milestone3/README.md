# Employee Wellness Management Analytics - Milestone 3

## Project Objective

The objective of Milestone 3 is to develop an Emotion Detection and Journal Analytics module that analyzes users' daily journal entries using Natural Language Processing (NLP) and Transformer-based deep learning models. The system detects the dominant emotion, calculates sentiment scores, and provides personalized wellness recommendations while securely storing the results for future analysis.
# Model Used
### Emotion Detection
- Transformer-based Emotion Classification Model
- Hugging Face Transformers
- PyTorch Backend
### Sentiment Analysis
- VADER (Valence Aware Dictionary for Sentiment Reasoning)
## Emotion Detection Pipeline
The journal entry follows the complete NLP pipeline before emotion prediction.`

User Journal Entry
        ↓
Language Detection
        ↓
Text Preprocessing
        ↓
Unicode Normalization
        ↓
Text Cleaning
        ↓
Tokenization
        ↓
Stop-word Removal
        ↓
Lemmatization
        ↓
Transformer Emotion Detection
        ↓
Confidence Score
        ↓
VADER Sentiment Analysis
        ↓
Wellness Recommendation
        ↓
Store Results in Database

## Confidence Score Calculation

The Transformer model predicts the probability of each emotion class.

- The emotion with the highest probability is selected as the dominant emotion.
- The corresponding probability is displayed as the confidence score.

Example:

| Emotion | Confidence |
|----------|-----------:|
| Joy | 98.42% |

## Sentiment Analysis

VADER is used to calculate the following sentiment scores:

- Positive Score
- Negative Score
- Neutral Score
- Compound Score

The compound score is stored in the database for future analytics.

Example:

| Score | Value |
|------|------:|
| Positive | 0.72 |
| Negative | 0.05 |
| Neutral | 0.23 |
| Compound | 0.91 |

## Database Schema

Each journal entry stores the following information:

- User ID
- Journal Text
- Detected Language
- Predicted Emotion
- Confidence Score
- Positive Score
- Negative Score
- Neutral Score
- Compound Score
- Wellness Recommendation
- Timestamp

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /journal | Submit a journal entry |
| POST | /emotion | Predict emotion from text |
| POST | /sentiment | Calculate sentiment scores |
| POST | /analyze | Perform complete journal analysis |

## Sample Input

Today I completed my assigned tasks successfully.
I feel proud and motivated to learn more.

## Sample Output

Detected Language : English

Predicted Emotion : Joy

Confidence Score : 97.84%

Sentiment Scores

Positive : 0.74
Negative : 0.03
Neutral  : 0.23
Compound : 0.91

Wellness Recommendation

Keep maintaining your positive mindset.
Celebrate your achievements and continue learning consistently.
## Technologies Used

- Python
- Google Colab
- Hugging Face Transformers
- PyTorch
- VADER Sentiment Analyzer
- NLTK
- pandas
- Streamlit
- FastAPI
- PostgreSQL (Neon Database)
- JWT Authentication

## Observations

- Successfully integrated a Transformer-based emotion detection model.
- Journal entries are processed through the complete multilingual NLP preprocessing pipeline.
- The system accurately predicts the dominant emotion along with its confidence score.
- VADER sentiment analysis provides detailed positive, negative, neutral, and compound scores.
- The generated wellness recommendation helps users better understand their emotional state.
- All analysis results are securely stored in the database for future analytics and reporting.

## Conclusion

This milestone successfully combines multilingual NLP preprocessing, Transformer-based emotion detection, sentiment analysis, and journal analytics into a unified system. The module serves as the foundation for future recommendation systems, wellness dashboards, and report generation in subsequent milestones.
