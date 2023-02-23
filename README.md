# myChatApp
A Simple Web Chat Application

***

## Installation
Follow the following steps to run the application
- clone the repository to your local system
```
git clone https://github.com/krishpranav/myChatApp.git
```

- install the require python modules
```
pip3 install websocket asyncio
```

- Start http server for front-end (use sudo if required)
```
python3 -m http.server 80 -b 127.0.0.1
```

- Start backend server
```
python3 backend/app.py
```

- Open the browser and type `127.0.0.1` in the URL to see the app working.