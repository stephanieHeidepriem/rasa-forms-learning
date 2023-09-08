# Introduction 
Chatbot by Course https://learning.rasa.com/rasa-forms-3/custom-actions/ 

Target: Add Feature - tell me the time

# Anpassungen nach rasa init
- Add Intent give_time to nlu.yml
- Add Story for it in storeis.yml
- Add Action action_show_time
- Add Intents and Actions to domain.config
- change endpoints.yml --> add 
  action_endpoint:
  url: "http://localhost:5055/webhook"

# Ausführen
- rasa run actions
- rasa shell