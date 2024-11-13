# Movie Recommendation Chatbot 🎬🤖

This is a conversational chatbot built using Python, TensorFlow, and NLP techniques that can recommend movies based on user input. It can provide recommendations based on specific movie titles or genres, making it an engaging and interactive movie recommendation system.

## Features

- **Movie Title Recommendation**: Suggests similar movies when provided with a specific title.
- **Genre-Based Recommendation**: Recommends movies based on user-preferred genres (e.g., action, comedy, sci-fi).
- **Natural Language Processing (NLP)**: Uses NLP techniques for intent classification and response generation.
- **Deep Learning Model**: Employs a neural network model for intent classification, trained on intents defined in `intents.json`.

## Getting Started

### Prerequisites

- Python 3.7+
- Required libraries: TensorFlow, Keras, NLTK, Transformers, Pandas, Numpy

### Dataset

- A movie dataset in CSV format, containing at least two columns:
  - **title**: The name of the movie.
  - **genres**: A list or description of genres associated with each movie.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-recommendation-chatbot.git
   cd movie-recommendation-chatbot
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
3. Ensure the movie dataset is named movies.csv and contains the required columns (title, genres).

## Interacting with the Bot:

- Enter a specific movie title to get similar movie recommendations.
- Ask for genre-based recommendations by specifying genres like "action," "romantic," etc.

## Key Functions

- **Intent Classification:** Uses a Sequential model to classify user intents based on patterns in intents.json.

- **Genre-Based Recommendation:** The chatbot retrieves movie recommendations based on the genre by filtering the movies.csv file.

- **Response Generation:** The bot provides relevant responses based on the user's intent, chosen randomly from predefined responses.

## Future Enhancements

- Improve Recommendations: Use collaborative or content-based filtering for personalized suggestions.
- Enhanced NLP: Integrate BERT or other transformer-based models for better intent detection.
- Deploy Chatbot: Implement on platforms like web applications or messaging apps.

# Enjoy your movie recommendations with the Movie Recommendation Chatbot! 🎉


### Tips:
- Update any paths or URLs based on your specific project structure.
- Adjust the `intents.json` and dataset sections if your actual implementation differs.
