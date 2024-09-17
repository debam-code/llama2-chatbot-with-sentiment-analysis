# llama2-chatbot-with-sentiment-analysis

This project showcases the development of an AI-powered chatbot that combines the Llama 2 model for generating text responses with sentiment analysis to tailor interactions based on the user's mood. The chatbot first checks a predefined question-answer (QA) dataset to see if a matching response exists. If no match is found, it generates a response using the Llama 2 model. Sentiment analysis is performed using the VADER tool to classify the user’s input as positive, negative, or neutral. Based on the detected sentiment, the chatbot adjusts its replies to create a more engaging and personalized user experience. The project leverages Hugging Face Transformers, Gradio, and Python.

