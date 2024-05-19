# ChatBot

# Chatbot Deployment with Flask Python



This gives 2 deployment options:
- Deploy within Flask Python app 
- Serve webview and also Flask prediction API.

## Initial Setup:
This repo currently contains the starter files.

Clone repo and create a virtual environment
```
$ git clone https://github.com/MohamedRafshan/ChatBot.git
$ cd ChatBot
if enviorment created 
$ .\Raf_venv\Scripts\Activate.ps1
if not 
$ python3 -m venv "NAME"
$ . "NAME"/bin/activate
```
Install dependencies
```
$ (venv) pip install Flask torch torchvision nltk
```
Install nltk package
```
$ (venv) python
>>> import nltk
>>> nltk.download('punkt')
```
Modify `intents.json` with different intents and responses for your Chatbot

Run
```
$ (venv) python train.py
```
This will dump data.pth file. And then run
the following command to test it in the console.
```
$ (venv) python chat.py
```





