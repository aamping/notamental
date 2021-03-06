# Notamental
## Description
Notamental is a note-taking mobile application running in Android, and IOS (still not tried). It is build in React-native and Redux. It has additional implementations:
- [React-native-elements](https://github.com/react-native-training/react-native-elements/) A modern design library with components to beautify the application
- [RNFirebase](https://github.com/invertase/react-native-firebase): Users and data are stored persistently in the cloud
- [OAuth Authentication](https://github.com/devfd/react-native-google-signin): Users can register and login easily using their Google account
- [React-native-voice](https://github.com/wenkesj/react-native-voice) (Speech to text): Users could write their notes using the Android Speech recognition in several languages
- [Dialog-Flow AI](https://dialogflow.com/) (TODO): Using an Artificial Intelligence agent, notes will be categorized automatically and suggest recomendation to the user.

![Gif Example](https://github.com/aamping/notamental/blob/master/notamental.gif)

Still not posted in any market app store

If you want to test it yourself:

## Requirements
Last version of:
- NodeJS
- NPM
- React-native-CLI
- Android Studio
- Android Emulator (I use AVD)

## Installation

Clone the project:
```
$ git clone https://github.com/aamping/notamental.git
```
Install dependencies
```
$ cd notamental
$ npm install
```
Database dependencies
- Create your own firebase project using this
https://rnfirebase.io/docs/v3.2.x/installation/initial-setup
- To make the Google Auth work:
https://github.com/devfd/react-native-google-signin/blob/master/android-guide.md

And then to run in android and start your packager:
```
$ react-native run-android
$ react-native start
```

### TODO
- Fix Logo
- Implement Dialog Flow agent for note lists
- Clean repository
- Others



