# Introduction 
Chatbot by Course https://learning.rasa.com/rasa-forms-3/rasa-forms/

Target: create Form
Form is a loop until all slots are set 

# Build and Test
## Voraussetzungen:
- Visual Studio Build Tools are installed (https://visualstudio.microsoft.com/de/visual-cpp-build-tools/)
- Python 3.8

## Install all dependencies 
## Install all dependencies in the virtual environment:
- Create the virtual environment: ```python -m venv ./env``` oder (because older version is needed) ```virtualenv --python="C:\Users\steph\AppData\Local\Programs\Python\Python38\python.exe" "venv"```
 --> you can also change the name to the environment. But make sure, that you don't commit it to the repository
- Enable the virtual environment: ```.\venv\Scripts\activate```
- check if pip version is up to date: ```python -m pip install --upgrade pip```
- install all requirements: ```pip install -r requirements.txt```

# Anpassungen nach rasa init
- add entity, slots and form into domain.yml
- Add rules for activate and deactivate form to rules.yml
- Add Stories

# Ausführen
- rasa run actions
- rasa shell