# DataLens
AI-powered data cleaning and insight assistant
# DataLens

AI-powered data cleaning and insight assistant that turns messy, raw restaurant data into clean, meaningful insights.

## About

DataLens takes a messy real-world dataset, cleans it, and uses an AI model (Google Gemini) to explain the data, debug errors automatically, and answer natural-language questions about it.

## Features

- **Data Cleaning**: Removes duplicates, fills missing values using median, fixes incorrect formats
- **Before/After Proof**: Shows data quality metrics before and after cleaning
- **Visualizations**: Charts showing restaurant distribution by area and rating patterns
- **AI Data Explainer**: Sends cleaned data summary to AI, which generates insights in simple language
- **AI Debugger**: When code throws an error, the error is sent to AI, which diagnoses the issue and suggests a fix
- **Ask Your Data**: Users can ask questions in plain English/Hindi, and the AI generates the pandas code to answer them

## Dataset

Zomato Restaurants Dataset (Bangalore) — downloaded from Kaggle. Contains 7,105 restaurant entries with ratings, cost, cuisine type, and location.

## Tech Stack

- Python
- pandas (data cleaning)
- matplotlib (visualization)
- Google Gemini API (AI integration)
- Google Colab (development environment)

## How It Works

1. Load raw dataset from Kaggle
2. Clean data: remove duplicates, handle missing values, fix formats
3. Generate visualizations (top areas, rating distribution)
4. Connect to Gemini AI via API
5. AI explains the data, debugs errors, and answers user questions

## Author

Priyaaa — Data Science student

## Future Scope

- Deploy as a Streamlit web app
- Add support for larger datasets
- Expand AI accuracy testing
