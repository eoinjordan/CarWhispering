# CarWhispering
 Car Whispering: the AI Mechanic  TinyML Audio Event Detection
 
Welcome to the AI Mechanic, an ambitious project that aims to build a global network of sharing of Machine Learning models trained and generated from a Mobile App and deployed on a handheld device that we can use to identify mechanical faults. 

The aim is to capture audio from our cars in the desired state, then record audio of them in a bad state (an air leak, perished bushing, worn brakes etc). Then as we fix our vehicles, we can annotate the data with the details collected from receipts of our repairs. 

Finally, the power will be given back to the car owner, allowing owners to have an educated best guess in mind about the cost of repairs before deciding if it's a wise investment.
 
### CarWhispering is currently reliant on the EdgeImpulse model created by me. Which I have published publicly via their site: [AIMechanic Trained Model](https://studio.edgeimpulse.com/studio/69300)

## What is this?
* This is a trained model to identify issues that typically don't throw error codes. The type of issue that a trained professional mechanic could identify by listening.

## What do I need to run it?
* You will need an AI Kit containing an [Arduino BLE Sense 33](https://store.arduino.cc/products/arduino-nano-33-ble-sense) and also a Grove LCD Display

## What model vehicle?
*  Initially only Petrol 6 cylinder BMW I have the commonly used engine code M54. Our first goal is to increase the models covered.

## Deploying
*Maven or a similar deployment will be implemented, along with a build and test pipeline. Apologies for now please refer to the [Arduino Quickstart]([Arduino BLE Sense 33](https://store.arduino.cc/products/arduino-nano-33-ble-sense))

## Care to join us?
* If you have an interest please send me a message. 
* Accepting contributors from all areas: mechanics, automation, build, electronics, documentation, test, development, ML, no qualifications necessary, beginners welcomed with open arms. 
