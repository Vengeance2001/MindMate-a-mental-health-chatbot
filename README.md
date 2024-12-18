# MindMate ChatBot with Flask and JavaScript


## Initial Setup:

Clone repo and create a virtual environment
```
$ git clone
$ cd chatbot-deployment
$ py3 -m venv venv
$ venv/bin/activate

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
Modify the `intents.json` with different intents and responses for your Chatbot

Run
```
$ (venv) python train.py
```
This will dump data.pth file. And then run
the following command to test it in the console.
```
$ (venv) python chat.py
```
To run the frontend version run below command in the terminal
```
$ (venv) flask run
```

