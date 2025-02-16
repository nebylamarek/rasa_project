# Chatbot based on rasa framework

### About
Conversational assistant is being developed to communicate with recruiters,
it can talk to you about my skills, experience or job preferences.

The assistant is still in development, it's my long-term hobby project.

This chatbot is being built using [Rasa](https://rasa.com/docs/getting-started/).

### Getting Started
Install [Rasa](https://rasa.com/docs/rasa/user-guide/installation/#installation).

### Visualization
[Graph](https://github.com/nebylamarek/Rasa_project/blob/master/graph.html)

This graph visualizes the internal patterns and rules of communication.

### Train the chatbot
```
rasa train
```

### Talk to the chatbot
```
rasa shell
```

### Run the chatbot integrated into the frontend site
[Frontend](https://github.com/nebylamarek/Rasa_project/blob/master/index.html)
```
rasa run -m models --enable-api --cors "*"
```
