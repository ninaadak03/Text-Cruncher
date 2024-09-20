# TextCruncher Web App

This web app allows users to summarize text using AI-powered models from Hugging Face. It is built using a combination of front-end and back-end technologies.

## Features
- Summarizes user-provided text using an AI model from Hugging Face.
- Built with the **bart-large-cnn** model developed by Facebook for summarizing content.
  
## Technologies Used
- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Node.js, Express.js
- **API**: Hugging Face API (bart-large-cnn model)

## How It Works
1. User enters text into a form on the web app.
2. The backend sends this text to the Hugging Face API, which uses the **bart-large-cnn** model to summarize the text.
3. The summarized version is then displayed to the user.
