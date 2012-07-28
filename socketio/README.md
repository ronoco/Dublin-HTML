# SocketIO Chatroom

1. Make sure you have installed [node.js](http://www.nodejs.org/#download) on your machine

2. Open a terminal terminal/cmd
3. In the window create a folder called chatroom on your machine
```
> mkdir chatroom
```
4. Copy the index.html and server.js from this project into the the folder
5. In the terminal/cmd window cd into the chatroom directory
```
> cd chatroom
```
6. Find out the IP address of your machine (ifconfig on mac, ipconfig on windows)
7. change the http://localhost in the index html to be the same as your computer.
```
var socket = io.connect('http://192.168.1.1');
```
**Your number will very likely be different than 192.168.1.1 that's fine**

8. Start the server with node (You may need to sudo on mac)
```
> node server.js
```
9. Open a browser and go to the URL that you entered in step 7.
10. Open another browser and go to the URL that you entered in step 7.
11. Enter text in one screen
12. See the text appear in the other screen
13. Tell your friends in the dojo your link and start chatting! 