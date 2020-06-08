# Chatbot
A recruiting bot build using RASA Framework.
## RASA Framework
Rasa stack consists of two major components: Rasa NLU and Rasa Core. Rasa NLU is responsible for natural language understanding of the chatbot. Rasa Core takes structured input in the form of intents and entities, and chooses which action the bot should take using a probabilistic model
## Getting Started
You can clone this project and follow the installation and setup section to run the bot
### Prerequisites
You show have `Python3.6` and `pip` manager installed on your machine.
### Installing
Here is how to install the dependencies
```
pip install -r requirements.txt
```
And then train the NLU model by,
```
python nlu_model.py
```
this will create a NLU model under `models` directory.<br>
And then train the Dialogue model by,
```
python train_dialogue.py
```
