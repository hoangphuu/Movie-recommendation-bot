# Movie Recommendation Bot

A conversational movie recommendation system powered by OpenAI and LangChain. This bot helps users discover great movies through natural language interaction.

---

##  Features

-  Chat-based interface for seamless interaction.
-  Movie recommendations based on user preferences.
-  Powered by OpenAI LLMs and LangChain for natural understanding.
-  Fetches movie metadata using OMDB API.
-  Context-aware suggestions based on previous inputs.

---

##  Installation

### 1. Clone the repository
```bash
git clone https://github.com/machinelearningzuu/awesome-llm-projects.git
cd awesome-llm-projects/12-movie-recommendation-bot
```
### 2. Create virtual environment & activate it
```bash
Copy
Edit
python -m venv venv
source venv/bin/activate       # On Linux/Mac
venv\Scripts\activate.bat      # On Windows
```
### 3. Install dependencies
```bash
Copy
Edit
pip install -r requirements.txt
```
## Configuration
Create a .env file in the project root and add your OpenAI and OMDB keys:
```bash
env
OPENAI_API_KEY=your_openai_api_key
OMDB_API_KEY=your_omdb_api_key
```
## How to Run
```bash
python app.py
```
This will launch a chatbot interface in your terminal.

## Project Structure
```bash
Movie-recommendation-bot/
│
├── app.py                  # Main app logic
├── chains.py               # LangChain chains
├── prompts/                # Prompt templates
├── utils.py                # Helper functions
├── requirements.txt
└── .env                    # API keys (not included in repo)
```
