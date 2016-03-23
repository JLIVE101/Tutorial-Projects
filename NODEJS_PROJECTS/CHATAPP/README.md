#Basic Chat Application

### Things you need to setup to get this working

* download & install node.js [here](http:://nodejs.org)
* download & install mongodb [here](http://mongodb.org)
* in Local Disk C: create a folder called **data** and within the data folder create another folder called **db**
* Open **TWO** CMD and navigate to the bin folder within the MongoDB directory and run **"mongod.exe"** to start the mongoDB server (in one cmd), then run **"mongo.exe"** to open the terminal for mongoDB (in the second cmd)
* In the mongoDB terminal type   `use chat;`
* Next type in `db.messages.insert({"name":"Server God", "message":"The first comment belongs to ME!"})`
* Almost done, now if you installed nodejs just navigate to the the folder that has `server.js` and run `node server.js` in a terminal.
* open index.html in a browser and duplicate them to see that they are all updated in realtime