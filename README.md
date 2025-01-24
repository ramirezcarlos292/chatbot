# 💬 Chatbot template

A simple Streamlit app that shows how to build a chatbot using OpenAI's GPT-3.5.

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://chatbot-template.streamlit.app/)

### How to run it on your own machine (venv)

1. Create new virtual environment

   ```
   $ python -m venv venv
   ```

2. Install the requirements

   ```
   $ pip install -r requirements.txt
   ```

3. Run the app

   ```
   $ streamlit run streamlit_app.py
   ```

### How to run it on your own machine (docker container)

1. Clone repository. Build the image container.
   ```
   $ docker build -t <image_name> .
   ```

2. 
   ```
   $ docker run -p <host_port>:<container_port(8501)> <image_name>

   on your web browser go to: localhost:8888
   ```
   
   or

1. Pull from docker hub
   ```
   docker pull ramirezcarlos292/chatbot-openai-streamlit
   ```

2. Run docker image
   ```
   docker run -p <host_port>:<container_port(8501)> ramirezcarlos292/chatbot-openai-streamlit:latest
   
   On your web browser go to: localhost:8888
   ```
