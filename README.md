# MiniCord
<p align="center">
  <img width="150" height="100" src="https://github.com/ThalKod/discord-clone/blob/master/MiniCord.png"> </br>
  A "Discord clone" with Socket.io, Node.js &amp; MongoDB... 
</p>

(Credits to ThatKod)

Fixed Username = Unique issue (people cannot sign up)

Removed Friedns list since it was useless and the feature wasnt added yet.


# :floppy_disk: Installation

```bash
# clone the repo

# install the node modules...
$ npm install

# start
$ npm start
```
Make sure you start mongodb or correct env var...
```js
config.dbURL = process.env.DATABASEURL || "mongodb://localhost/minicord";
```


## Built with

* [Socket io](https://github.com/socketio/socket.io) - Realtime application framework
* [Nodejs](https://github.com/nodejs/node) - Node.js JavaScript runtime

## Upcomming Features
- [ ] Friends Request, sending/add people to friends list...
- [ ] Real time one to one chat with friends...
- [ ] Direct message friends...
- [ ] Received Message Notifications...
- [ ] Emoji Sharing...
- [ ] Image Sharing within chat...
- [ ] Files Upload and sharing...
