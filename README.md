# rasa-x-with-web

## Blog 
This repository is build while writing this blog https://medium.com/analytics-vidhya/create-a-simple-chatbot-with-rasa-x-and-integrate-with-web-6c8c9338ce3 .

## Steps to see demo
1. Install requirements
```
$ pip install rasa-x==0.34.0 --extra-index-url https://pypi.rasa.com/simple
```


2. Start rasa actions server
```
$ rasa run actions
```


3. Start rasa-x if you want to change intent, dialogue and train it again or skip this step.
```
$ rasa x
```


4. Start rasa api server
```
$ rasa run --cors "*" --enable-api
```


5. Open index.html in any browser
