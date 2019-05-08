# Spark - a simple injector for Electron applications
Spark allows you to inject JavaScript into running Electron apps by using the `--remote-debugging-port` switch from the chrome devtools protocol.  

# Configuration
All you'll need to configure Spark is to edit the main config variables within the SparkInjector.py file.  
Configuration options included:
- baseurl - The browser URL to inject into.
- injectionjs - The JS to inject into the browser.
- The port to inject into

# Requirements
- Requests
- Colorama
- Websocket-client

# About
This is my first graphical application that is not a web application and I wanted to release it as an example and as a tool for those who want to inject into Electron applications.
