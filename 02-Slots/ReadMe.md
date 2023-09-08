# Introduction 
Chatbot by Course https://learning.rasa.com/rasa-forms-3/slots/

Target: Save information over a long period of time --> remember shirt-size

# Anpassungen nach rasa init
- add Examples in nlu.yml
- add intents, entities, slots, responses and actions to domain.yml
- add stories to stories.yml
- change configuration -> Pipeline and Policies needed
    o without pipelines no Entity-Extraction possible
    o without policies no Slot-Use
- Add Custom Action
- Action Endpoint hinzufügen in endpoints.yml

# Ausführen
- rasa run actions
- rasa shell