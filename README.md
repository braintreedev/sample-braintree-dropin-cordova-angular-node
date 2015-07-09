# braintree-dropin-cordova-angular-node
Braintree Dropin built with Node on the backend and Apache Cordova (used to create the mobile app for iOS and Android).

## 1) NODE SERVER: Installation and usage

* Navigate to `/node-server`
* Run `npm install` to install all dependencies
* Run `npm start` to start the Express app

## 2) CORDOVA APP: Usage

* Open a new terminal (or prompt) window (don't stop NODE SERVER)
* Navigate to `/cordova-app`

* **Important:** Make sure you have your computer configured for Cordova: [video tutorial](https://www.youtube.com/watch?v=V7u0caTdjBQ)

* Run `cordova run ios --simulator` to test the app on iOS Simulator
* Run `cordova run ios --device` to test the app on iOS devices connected via USB
* Run `cordova run android` to test the app on Android devices connected via USB

* Fill in the form using a Credit Card:
    * Number: `4111 1111 1111 1111`
    * CVV: `123`
    * Expiration date: `11/2020`
    
## Useful links

* [v.zero](https://www.braintreepayments.com/v.zero)
* [The Braintree Node.js SDK](https://developers.braintreepayments.com/javascript+node/sdk/server/overview)
