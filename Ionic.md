# Ionic

## Quick Start
* [Ionic Cheatsheet](https://devdactic.com/ionic-cheatsheet/)

## Hello World
* [Getting Started with Ionic Framework](http://www.blaiseliu.com/getting-started-with-ionic-framework/)

## Documentation
* [Ionic Documentation](http://docs.ionic.io/docs)

## Ionic CLI
* [CLI commands](https://github.com/TwoGears/hakomo-guides/wiki/Ionic-cheatsheet)
* [Ionic CLI](https://github.com/driftyco/ionic-cli)


## Question
Ionic vs ionic Enterprise


## Tools
play.ionic.io

## Debug Ionic

Debug Ionic Android Application On Mobile Devices or Emulators
```java
#Method #1
ionic run android -l -c

#Method #2
chrome://inspect/#devices

#Method #3
use Android Device Monitor provided in Android sdk tools
```

## Awesome List
* [Ionic Adventures](https://github.com/juarezpaf/ionic-adventures) - The ultimate guide to learn Ionic 

## Starter Apps
* [A Comprehensive List Of Ionic Starter Apps](http://www.gajotres.net/a-comprehensive-list-of-ionic-starter-apps/)


## Best Practice

## Projects
* [Realworld Examples](https://github.com/lockeyo/Ionic-Framework-Resources/blob/master/realworld-examples.md)
* [Instachat](https://github.com/gregavola/instachat)
* [Ionic Recorder](https://github.com/tracktunes/ionic-recorder)
* [Generator Ionic](https://github.com/diegonetto/generator-ionic)
* [building a complete mobile app with ionic framework](https://github.com/ionicthemes/building-a-complete-mobile-app-with-ionic-framework)
* [Production ready apps with ionic framework](https://github.com/airpair/production-ready-apps-with-ionic-framework)
* [Ionic Ebook](https://github.com/innovieco/ionic-ebook)
* [Facebook login with ionic framework](https://github.com/ionicthemes/facebook-login-with-ionic-framework)
* [IonicFramework Templates](https://github.com/HansUXdev/IonicFramework-Templates)
* [Awesome Ionic](https://github.com/chrisbernal/awesome-ionic)
* [Salesforce REST API Ionic Framework App Sample](https://github.com/myurasov/Salesforce-REST-API-Ionic-Framework-App-Sample)
* [Ionic Geolocation Demo](https://github.com/Gajotres/IonicGeolocationDemo)
* [Ionic Framework Resources](https://github.com/lockeyo/Ionic-Framework-Resources)
* [Generator Ionic](https://github.com/mikehaas763/generator-ionic)
* [Ionic boilerplate](https://github.com/cowfox/ionic-boilerplate)
* [Ionic framework tutorial](https://thinkster.io/ionic-framework-tutorial)

## Good List

* [40+ Ionic Framework 2 Resources](http://mcgivery.com/15-ionic-framework-2-resources/)
* [240+ Ionic Framework Resources](http://mcgivery.com/100-ionic-framework-resources/)
* [Hello World: Your First Ionic Framework App](http://mcgivery.com/hello-world-first-ionic-framework-app/)
* [Hello Backend: Your Second Ionic Framework App](http://mcgivery.com/hello-backend-your-second-ionic-framework-app/)
* [Hello Modules: Your Third Ionic Framework App](http://mcgivery.com/hello-modules-your-third-ionic-framework-app/)
* [Debugging Ionic Apps using Chrome Developer Tools](http://mcgivery.com/debugging-ionic-apps-chrome-developer-tools/)
* [Using Custom URL Schemes In Your Ionic Framework App](http://mcgivery.com/using-custom-url-schemes-ionic-framework-app/)
* [Ionic: Master Detail Pattern](http://mcgivery.com/ionic-master-detail-pattern/)
* [Modules in Ionic/Angular](http://mcgivery.com/modules-ionicangular/)
* [Ionic: Using Factories and Web Services for Dynamic Data](http://mcgivery.com/ionic-using-factories-and-web-services-for-dynamic-data/)
* [AngularJS Mobile Apps with Ionic and Backand](http://blog.backand.com/angularjs-mobile-apps-with-ionic-and-backand/)
* [Present Ionic](http://ionicframework.com/present-ionic/slides/#/1)
* [Ionic Framework Demo - Matt Stauffer](https://www.youtube.com/watch?v=nh9EARpk-dc)
* [Ionic Command Line Interface (CLI)](http://www.joshmorony.com/getting-started-with-the-ionic-command-line-interface-cli/)
* [Getting Started with Ionic](http://blog.teamtreehouse.com/getting-started-ionic)
* [Ionic Angularjs and Firebase equals hybrid heaven](http://blog.budacode.com/2015/06/09/ionic-angularjs-and-firebase-equals-hybrid-heaven/)
* [Using the $http Service](http://www.joshmorony.com/part-1-using-the-http-service-in-ionic-to-dynamically-load-google-map-markers/)
* [Monitoring Online and Offline States in an Ionic Application](http://www.joshmorony.com/monitoring-online-and-offline-states-in-an-ionic-application/)
* [Installing ngCordova in an Ionic Application](http://www.joshmorony.com/installing-ngcordova-in-an-ionic-application/)
* [Integrating Google Maps with an Ionic Application](http://www.joshmorony.com/integrating-google-maps-with-an-ionic-application/)
* [Ionic Framework](https://www.script-tutorials.com/ionic-framework/)



## Code Snippets

### Prerequisite
```java
npm install -g cordova ionic

npm install -g ios-sim
npm install -g ios-deploy

#Update Ionic lib
ionic lib update

#Starting an Ionic App
ionic start myapp [template]

ionic serve [options]
ionic setup sass 
ionic serve --lab

#Specifying an IP Address to use
ionic serve --address 68.54.96.105

#Gathering information about your runtime
#ionic info

```

### iOS Prerequisite
* OSX
* Xcode

```java
npm install -g ios-sim

# Add iOS platform for cordova
ionic platform remove ios
ionic platform add ios

# Build Debug version
ionic build ios

# Build Prod version
ionic build ios --release 

# Run your code within the emulator
ionic emulate ios

# Run your code on real device if connected
ionic run ios

ios-sim launch platforms/ios/build/emulator/your_ionic.app

ionic serve
```

### Android Prerequisite
* Android SDK
* Ant


```java
# Path to your sdk in your file system
export ANDROID_HOME=~/Library/Android/sdk

# Add iOS platform for cordova
ionic platform add android

# Build Debug version
ionic build android

# Build Prod version
ionic build android --release 

# Run your code within the emulator
ionic emulate android

# Run your code on real device if connected
ionic run android

ionic serve
```

### Add plugins
```java
# add a toast plugin
ionic plugin add nl.x-services.plugins.toast

Splashscreens and Icons

# generate both icons and splashscreens
ionic resources

# generate only icons
ionic resources --icon

# generate only splashscreens
ionic resources --splash
```

### Ionic View
```java
ionic login
ionic upload
ionic share EMAIL


```




	
* [Ionic CLI](https://github.com/driftyco/ionic-cli)
* [Ionic](https://github.com/driftyco/ionic)
* [ionic Adventures](https://github.com/juarezpaf/ionic-adventures)
* [Ionic Base App](https://github.com/driftyco/ionic-app-base)

