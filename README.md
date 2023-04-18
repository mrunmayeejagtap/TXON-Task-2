
# ChatBot

## Installing Flask

In your terminal run the requirements.txt file using this pip

```
pip install -r requirements.txt
```

## About the ChatBot 

This chatbot was created using Microsoft DialoGPT, a pre-trained language model, and Flask, a Python web framework. The frontend was created using HTML, CSS, and JavaScript, with jQuery used to handle HTTP requests.

The Flask app handled incoming chat messages and used AJAX to update the chat interface in real-time. The DialoGPT model was fine-tuned to improve its accuracy, and the app was deployed to a web server.

By the end of the project, I gained experience in using a pre-trained language model, a Python web framework, and web development technologies to create a chatbot that could communicate with users.

# ChatBot Link
The Chatbot is constructed using the Microsoft/DialoGPT-medium model.

```
https://huggingface.co/microsoft/DialoGPT-medium
```

# User-Html

```
var userHtml = '<div class="d-flex justify-content-end mb-4"><div class="msg_cotainer_send">' + user_input + '<span class="msg_time_send">'+ time + 
    '</span></div><div class="img_cont_msg"><img src="https://i.ibb.co/d5b84Xw/Untitled-design.png" class="rounded-circle user_img_msg"></div></div>';
```

# Bot-HTML

```
var botHtml = '<div class="d-flex justify-content-start mb-4"><div class="img_cont_msg"><img src="https://i.ibb.co/fSNP7Rz/icons8-chatgpt-512.png" class="rounded-circle user_img_msg"></div><div class="msg_cotainer">' + bot_response + '<span class="msg_time">' + time + '</span></div></div>';
```
