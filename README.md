# Lab8-Starter
Angie Nguyen
URL: 

Service workers are one tool to implement graceful degradation, which involves starting with the max technology and addressing lower levels by preserving core functionality when the max technology is not supported. In this case, service workers were used to fallback on previously cached values when the application is currently unable to make a successful request to the server (such as the case when it is offline). Thus the recipe list was still able to be viewed even when the device was currently offline, providing an alternative so the app functions without the "max technology" of being connected to the internet. When the app does have the max technology, then it utilizes it by making a request to the provided URLs, updating the recipe list with new values. 