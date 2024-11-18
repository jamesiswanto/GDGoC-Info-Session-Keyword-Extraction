# Info Session Feedback Analysis and Visualization System

## Project Overview
This project processes and visualizes participant feedback from Info Session 2024. The system:
- **Summarizes Feedback**: Extracts and categorizes textual feedback into concise and actionable points.
- **Generates Word Clouds**: Provides a visual representation of frequent keywords and themes.
- **Enables Insights**: Helps organizers identify strengths and areas for improvement.

## Features
- **Data Cleaning**: Preprocesses raw feedback text, removing noise and unnecessary words.
- **Categorical Analysis**: Groups feedback into predefined themes such as:
  - Sound/Audio
  - Consumables
  - Duration
  - Interactivity
  - Speakers
  - Session Management
  - Atmosphere
  - Technical Issues
- **Visualization**: Creates word clouds to showcase dominant themes.

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `pandas` for data manipulation
  - `re` for text cleaning
  - `WordCloud` for visualization
  - `matplotlib` for displaying visuals
- **File Format**: CSV for input data

## Getting Started
### Prerequisites
- Python 3.8 or above
- Install required libraries:  
  ```bash
  pip install pandas matplotlib wordcloud
  ```

### How to Use
- Input Data: Place your feedback data in a CSV file with appropriate column names.
- Run the Script: Execute the Python script to process feedback and generate visualizations.
- Output: View categorized feedback summaries and the word cloud image.

### Sample Code
```python
from wordcloud import WordCloud
import pandas as pd

# Example: Generating a Word Cloud
feedback_text = "Sample feedback text"
wordcloud = WordCloud(background_color='white').generate(feedback_text)
```

### Example Outputs
- Feedback Summary: Categorized text output
- Word Cloud: Visual highlighting frequent words

## Skills and Expertise
### This project demonstrates
- Text Mining
- Natural Language Processing (NLP)
- Data Visualization
- Python Programming

## Future Enhancements
- Incorporate sentiment analysis to gauge positive, negative, or neutral feedback.
- Add interactive dashboards using Plotly or Dash.
- Explore machine learning models for automated feedback categorization.
