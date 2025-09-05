# Crusader

<img width="1694" alt="Screenshot 2024-10-06 at 10 38 16 PM" src="https://github.com/user-attachments/assets/f8ff2672-44be-4137-8248-7c1ac9e5f046">

## To Run Locally

python3 (< 3.13)

### Env Keys
GOOGLE_API_KEY, GOOGLE_GEN_KEY @ https://console.cloud.google.com/apis/credentials  
GOOGLE_SEARCH_ENGINE_ID @ https://programmablesearchengine.google.com  
REDDIT_CLIENT_ID, REDDIT_SECRET @ https://www.reddit.com/prefs/apps  
REDDIT_USERNAME, REDDIT_PASSWORD @ https://www.reddit.com/login  
FLASK_SECRET_KEY   
```
python3.12    
>>> import os   
>>> os.urandom(24)  
```  

### Build Client  
In /Crusader/client:  
`npm i`  
`npm run build`  

### Setup Server  
In /Crusader/server:    
`python3.12 -m venv venv`    
`source venv/bin/activate`  
`pip3 install -r requirements.txt`   

### Run App   
In /Crusader:  
`python3.12 -m server.app`  


