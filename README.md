# Project 5 - MQTT leaflet Webpage

## Overview

This project is a webpage that uses a leaflet map background in addition to a mqtt messaging system that allows for the sending of messages and information. The page itself is a map that allows the user to connect to a mqtt service and publish their location. They may also subscribe to any topic and publish a message in that topic. 
### File Structure

#### JavaScript Files  

1. **Script.js**
   - This is where the backend of the web app lies, it contains all the functions and scripting used to link the information on the webpage to MQTT and also ensure all the buttons are working correctly.
   
#### HTML Files

1. **Index.HTML**
   - This is the main and only page of this web app, it is very simple and contains the stylesheets required for the plug-ins. The main body contains the map itself and the MQTT tools, like the broker, port topic and message, along with the share location button and the publish message.

   
#### Stylesheets

1. **style.css**
   - CSS stylesheet used for the HTML.
