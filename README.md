# node-red-contrib-tjbot
This Package will contain all necessary NodeRed Nodes for the IBM Watson TJBot including Bluemix Watson IoT & Bluemix Watson services based on the great Node-Red Flowset.

With this demonstration you will be able to send sensordata from your raspberry pi to Bluemix (via IoT Foundation) and then respose to them. 
Also you can send commands like speak, translate, transcribe (from the mico detached to the raspberry pi), get image and analyze, get weather, detect emotions out of the text and also using chatbot as a conversation. 

# under construction !!

This package will include all needed nodes to enhance the TJBot from IBM Research with special functionality. 

Nodes will be 
    TakePhoto (node-red-contrib-camerapi)
    Speaker (node-red-contrib-speakerpi)
    Microphone (node-red-contrib-micropi)

Also it will use node-red-contrib-grovepi for sensors and outputs if using the GrovePi Starterkit or you can use the raspberry pi senseHAT. 

## Raspberry Pi installation 
See the "Install Raspberry Pi.txt" for the installation of the environment. 

## NodeRed Raspberry Pi installation
Copy the flows of the directory Flows/GrovePi into an instance of NodeRed on your Raspberry Pi using GrovePi Starterkit. Please check all of the watson nodes and also the IOT Foundation Node for Bluemix having the proper credentials set out of your environment.

## Bluemix installation
Copy the flows of the directory Flows/Bluemix into an instance of NodeRed on Bluemix. You also should have the watson services bound to that environment.

## Complete Tutorial 

## Youtube Video of this demonstration

### Excample-flows

