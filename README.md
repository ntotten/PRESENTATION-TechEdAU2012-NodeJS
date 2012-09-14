# TechEd Australia 2012 - Node.js Samples
===========================

This is the demo that was built in my Node.js and Windows Azure talk at TechEd Australia 2012.

# Demo Steps

## Hello Node
	* node-server snippet

## New Express Site
	* node site create [name] --git
	* npm install express
	* rename app.js server.js
	* subl .
	* node server.js
	* git deploy

## Debugging and Running Locally
	* DEMO SETUP: npm install node-inspector -g
	* node --debug server.js
	* DEMO SETUP: npm install supervisor -g
	* node-inspector
	* supervisor server.js
		Change route, refresh

## Add socket.io
	* npm install socket.io
	* index snippet
	* socketio-server snippet
	* socketio-connect snippet
	* deploy

## Add Table Storage
	* npm install azure
	* table-create snippet
	* table-save snippet
	* deploy
	* Show Cloud Storage Studio

## Web Matrix
	* New Starter Site
	* Deploy