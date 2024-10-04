# Flare Fashion Recommendation

Flare is a fashion recommendation system that suggests outfits based on events and provides explanations for why certain items match. It uses machine learning and image recognition to analyze clothing pieces, offering personalized recommendations for various occasions.

## Features
- **Outfit Matching**: Recommends combinations of clothes that match based on style, color, and occasion.
- **Reasoning**: Provides explanations for why the recommended items go well together.
- **Event-based Suggestions**: Recommends outfits suitable for specific events (e.g., casual, formal, etc.).
- **Multi-platform**: Available as both a mobile app and a website.

## Technologies Used
- **Llama2**: For natural language understanding and generating explanations for outfit choices.
- **Clarifai API**: For image recognition and analysis of fashion items.
- **Python**: Backend programming language.
- **Flask**: Web framework for the API.
- **HTML/CSS**: Frontend for the web version.

## Installation

### Prerequisites
- Python 3.x
- Required Python packages (see `requirements.txt`)

### Steps to Run
1. Clone the repository:
   ```bash
   `git clone https://github.com/Rabia-Usman/llama_clarifai.git`
2. Navigate to the project directory:
   `cd llama_clarifai`
3. Install the required dependencies:
   `pip install -r requirements.txt`
4. Run the application:
   `python app.py`
### Usage
1. Upload images of your clothing items.
2. Select an event or occasion (e.g., party, casual day out).
3. Receive outfit recommendations along with explanations on why certain items go well together.
