# sHome - Ionic Bluetooth Control App :space_invader: :tooth:
This repository contains the source code for an Ionic Framework-based mobile application called "sHome" that allows users to control devices through Bluetooth. The app is specifically designed for Arduino-based projects where data is sent to the microcontroller via Bluetooth. Here's a step-by-step guide on setting up the app and connecting it to a Bluetooth-enabled device.

## Prerequisites
Before you begin, make sure you have the following installed:

- [Node.js ](https://nodejs.org/en)
- [Ionic CLI](https://ionicframework.com/docs/cli)

## Installation
Go inside the cloned code and run the below command to install all the packages
```
$ npm install
```

## Testing
To test the app, use the Ionic live server with the following command
```
$ ionic serve
```
This command will launch the app in a local web browser. Note that Cordova plugins won't work in this environment. For full testing capabilities, deploy the app on an Android emulator or a physical Android device.

## Usage
- <b>Enable Bluetooth on Your Mobile Device:</b><br/>
Ensure that Bluetooth is turned on in your mobile device settings before launching the app. This ensures a seamless connection with Bluetooth-enabled devices.
- <b>Pairing with Devices:</b><br/>
Within the app interface, explore the list of available devices and pair with them effortlessly. The app provides an intuitive pairing mechanism, simplifying the process for users.
- <b>Device Selection and Connection:</b><br/>
Once paired, select the desired device from the list to establish a connection. The app facilitates easy device selection, enabling quick and efficient connections.
- <b>Data Transmission:</b><br/>
Leverage the app's functionalities to send and receive data between your mobile device and the connected hardware. Use the app as a conduit for transmitting commands or information to your Arduino-based project.
