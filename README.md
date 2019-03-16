# React-native-HelloWorld
HelloWorld application in React native to run on android or ios device
Setup

https://facebook.github.io/react-native/docs/tutorial 

Before attempting to run this demo please make sure that you have taken care of the following dependencies

Ensure that you have node installed and then use npm to install react native as described below

Installing node The simplest way to get started is to install homebrew on your system. You can then install node and watchman with the following commands

brew install node brew install watchman Installing React-Native Command Line Interface You may install react-native with the following npm command

npm install -g react-native-cli once this is complete, navigate to this projects folder and type npm install to install all dependencies listed in the project's package.json file

Configuring the environments for iOS and Android iOS (XCode)

Navigate to project ios subfolder and run

pod install to install the latest iOS MotionDNA SDK

Android (Android Studio)

Open the Android project folder in Android Studio Aside from instant run, install any recommended dependencies and build tools that are suggested

Running the demos The hello world project is designed to work with both ios and android systems. It will run on the simulator or the actual device.

You can start streaming the app to your device with the following commands

For iOS

react-native run-ios For iOS you will probably want to have the simulator open already as XCode 9 does not start the simulator automatically with this command

For Android adb reverse tcp:8081 tcp:8081 sudo react-native run-android

#additional commands adb devices ----- to see devices connected sudo npm start
