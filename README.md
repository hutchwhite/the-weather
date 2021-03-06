# The Weather


## Information
This is small Ionic project displaying the forecast of your location (or one you can enter) using the DarkSky API. 

---


## Installation

### Requirements

Below you will find basic setup and deployment instructions for this project. To begin you should have the following applications installed globally on your local development system:

  + git >= 2.0.2
  + node >= 4.3.1
  + npm >= 2.11.1
  + bower >= 1.4.1
  + ionic < 2

### Packages
  + `npm install`
  + `npm install -g bower`
  + `npm install -g gulp`
  + `bower install`
  + `gem install scss_lint`
  
### Cordova
  + `cordova plugin add cordova-plugin-geolocation`
  
---

## Gulp

Gulp is simple to run.  Each Gulp task is broken up under Gulp\tasks.  This keeps the task manager clean and concise.

To build the app, simply run `gulp`.

---

## Build and Testing

To test or run this application first run gulp, then you can run any of the following:
  + `ionic serve --lab` - will launch a web browser showing you both iOS and Android
  + `ionic emulate ios` - this will launch the app in the xcode emulator
  + `ionic build ios` - this will create the build for the xcode project. You'll find this soluiton under the repo root/packages/ios



