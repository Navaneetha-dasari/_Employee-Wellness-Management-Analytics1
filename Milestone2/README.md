# Employee Wellness Management Analytics - Milestone 2

## Project Objective

The objective of this milestone is to build a multilingual NLP Text Preprocessing Pipeline that prepares raw text for sentiment analysis and emotion detection. The pipeline cleans, normalizes, and transforms text into a machine-learning-ready format.

## NLP Pipeline Overview

The implemented pipeline performs the following steps:

- Accept text through direct input
- Upload and process TXT and CSV files
- Detect the language of the input text
- Unicode text normalization
- Text cleaning
- URL removal
- Email removal
- HTML tag removal
- Emoji extraction and removal
- Punctuation removal
- Number removal
- Lowercase conversion
- Tokenization
- Stop-word removal
- Lemmatization
- Noise filtering
- Display intermediate outputs after every preprocessing stage

## Technologies and Libraries Used

- Python
- Google Colab
- NLTK
- spaCy
- langdetect
- emoji
- regex
- pandas
- unicodedata
- re (Regular Expressions)

## Google Colab Setup Instructions

1. Open the notebook in Google Colab.
2. Install the required libraries.
3. Run all notebook cells in sequence.
4. Enter text manually or upload a TXT/CSV file.
5. View the preprocessing outputs and analysis results.

## Preprocessing Workflow

Input Text
↓
Language Detection
↓
Unicode Normalization
↓
Text Cleaning
↓
Remove URLs
↓
Remove Emails
↓
Remove HTML Tags
↓
Extract & Remove Emojis
↓
Remove Punctuation
↓
Remove Numbers
↓
Convert to Lowercase
↓
Tokenization
↓
Stop-word Removal
↓
Lemmatization
↓
Noise Filtering
↓
Final Preprocessed Text

## Sample Input

I am feeling very happy today! 😊 

### Sample Output

- Detected Language: English
- Cleaned Text: I am feeling very happy today
- Extracted Emoji: 😊
- Tokens: ['i', 'am', 'feeling', 'very', 'happy', 'today']
- Tokens after Stop-word Removal: ['feeling', 'happy', 'today']
- Lemmatized Tokens: ['feel', 'happy', 'today']
- Final Preprocessed Text: feel happy today

## Observations

- The pipeline successfully preprocesses multilingual text.
- Language detection works before preprocessing.
- Emojis are extracted separately for emotion analysis.
- Noise such as URLs, emails, HTML tags, punctuation, and numbers is removed.
- The processed text is suitable for sentiment analysis and emotion classification.
