# recan-firebase-authentication

## Features

* uses:
  * only React (create-react-app)
  * firebase 5.0.0
  * react-router 4.2.0
  * no Redux/MobX
  * [React's 16.3 context API](https://reactjs.org/blog/2018/03/29/react-v-16-3.html)
* features:
  * Sign In
  * Sign Up
  * Sign Out
  * Password Forget
  * Password Change
  * Protected Routes with Authorization
  * Database: Users

## Installation

* `git clone https://github.com/StartupRobotSUT/recan-firebase-authentication.git`
* `cd recan-firebase-authentication`
* `npm install`
* `npm start`
* visit http://localhost:3000/
* Use your own Firebase Credentials

### Use your own Firebase Credentials

* visit https://firebase.google.com/ and create a Firebase App
* copy and paste your Credentials from your Firebase App into src/firebase/firebase.js
* activate Email/Password Sign-In Method in your Firebase App
