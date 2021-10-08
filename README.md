# bHostVideo Meet Now

An application customized by bTeam

#### How it is?
A Video Chat app build with NodeJS, Express, Peerjs, Socket.io

# Commit rules
 ### Please, view in COMMIT.md

# Video-chat-v1

Video-chat-v1 is a video chat app that makes it easy to groups up with people you want to meet

![IMG](./video-chat.png)

Check out the live demo: https://video-chat-app-v1.herokuapp.com/

An article I wrote which explains how I build this: https://bit.ly/3wh0gyR

This app is build using NodeJS, Socket.io, and Peerjs(WebRTC)

## How to run the project?

1. Clone this repository in your local system.
2. Open the command prompt from your project directory and run the command `npm start`.
3. Go to your browser and type `http://127.0.0.1:5000/` in the address bar.
4. Hurray! That's it.

### ToDo

- [ ] - Release v2 stable

# Recent Build Log

### 2021/08/10 at 18:23

-----> Building on the Heroku-20 stack
-----> Using buildpack: heroku/nodejs
-----> Node.js app detected
       
-----> Creating runtime environment
       
       NPM_CONFIG_LOGLEVEL=error
       NODE_VERBOSE=false
       NODE_ENV=production
       NODE_MODULES_CACHE=true
       
-----> Installing binaries
       engines.node (package.json):  unspecified
       engines.npm (package.json):   unspecified (use default)
       
       Resolving node version 14.x...
       Downloading and installing node 14.18.0...
       Using default npm version: 6.14.15
       
-----> Restoring cache
       Cached directories were not restored due to a change in version of node, npm, yarn or stack
       Module installation may take longer for this build
       
-----> Installing dependencies
       Installing node modules
       
       > ejs@3.1.3 postinstall /tmp/build_06408033/node_modules/ejs
       > node --harmony ./postinstall.js
       
       
       > nodemon@2.0.4 postinstall /tmp/build_06408033/node_modules/nodemon
       > node bin/postinstall || exit 0
       
       Love nodemon? You can now support the project via the open collective:
        > https://opencollective.com/nodemon/donate
       
       added 254 packages in 3.868s
       
-----> Build
       
-----> Caching build
       - node_modules
       
-----> Pruning devDependencies
       audited 254 packages in 2.145s
       
       9 packages are looking for funding
         run `npm fund` for details
       
       found 8 moderate severity vulnerabilities
         run `npm audit fix` to fix them, or `npm audit` for details
       
-----> Build succeeded!
-----> Discovering process types
       Procfile declares types     -> (none)
       Default types for buildpack -> web
-----> Compressing...
       Done: 35M
-----> Launching...
       Released v68
       https://bhostvideo-meeting-v1.herokuapp.com/ deployed to Heroku
       
### This is the end of README
