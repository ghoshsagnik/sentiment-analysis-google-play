# Instructions to Run

### 1. Creating an Ngrok account and using Authentication key
- **SignUp on https://ngrok.com/**
- **This will give an authentication key**
- **Paste the Authentication Key in Backend Flask App/Google_play_sentiment_analysis.ipynb**
  ```python
      # Set ngrok authtoken (replace with your actual token)
      ngrok.set_auth_token("Paste ngrok authentication token here")
  ```
### 2. Running the flask app and Using the public URL
- **Run the Flask App**
  After installing libraries the execution continues to run and this shows
  
![Screenshot 2025-02-04 205744](https://github.com/user-attachments/assets/969c3ad9-972d-43e8-84fd-ad706de44ec5)


- **Copy the link pointed to in the image**
- **Open the html file in any IDE
- Paste the link in Frontend Webpage/sentiment_analysis.html**
  
  ```const publicUrl = "Update with your ngrok public URL"; ```
  
  Note: I have used Ngrok. You can use ```Streamlit```
  
### 3. Double click to oprn the html file in browser

### 4. Paste Google Play App link in the text box

### 5. Click **Generate Reviews** for showing all the text reviews and **Generate Sentiment** for showing the sentiment result.

!![Screenshot 2025-01-19 100537](https://github.com/user-attachments/assets/2108b2b1-0d8c-4058-9a61-cbcdc84d093a)

