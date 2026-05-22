# 🤖 Mood Based AI Chatbot

A Streamlit chatbot powered by Mistral AI that responds in different personality modes.

## Modes
- 😡 Angry
- 😂 Funny
- 😢 Sad
- 🔥 Roasting
- 🎭 Poet

## Local Setup

1. Clone the repo and install dependencies:
```bash
pip install -r requirements.txt
```

2. Create a `.env` file in the root folder:
```
MISTRAL_API_KEY=your_mistral_api_key_here
```

3. Run the app:
```bash
streamlit run chatbot.py
```

## Deploy on Streamlit Cloud

1. Push this repo to GitHub
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Click **New app** → select your repo → set main file as `chatbot.py`
4. Under **Advanced settings → Secrets**, add:
```
MISTRAL_API_KEY = "your_mistral_api_key_here"
```
5. Click **Deploy** ✅
