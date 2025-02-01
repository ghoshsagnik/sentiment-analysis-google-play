# Requirements

### 1. Create an Ngrok account
- **SignUp on https://ngrok.com/**
- **This will give an authentication key**
### 2.Paste the Authentication Key in Backend Flask App/Google_play_sentiment_analysis.ipynb
{
  "cells": [
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "yEW5SvWLePLo"
      },
      "outputs": [],
      "source": [
        "# Install required libraries\n",
        "!pip install flask flask-ngrok flask-cors transformers google-play-scraper pyngrok\n",
        "\n",
        "from flask import Flask, request, jsonify\n",
        "from flask_cors import CORS  # Import CORS\n",
        "from pyngrok import ngrok\n",
        "import pandas as pd\n",
        "from google_play_scraper import Sort, reviews_all\n",
        "from transformers import pipeline\n",
        "import re\n",
        "\n",
        "# Set ngrok authtoken (replace with your actual token)\n",
        "ngrok.set_auth_token(\"Paste ngrok auth token here\")\n",
        "\n"
        ]
      }
     ]
     }
