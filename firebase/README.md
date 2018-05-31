# Welcome to Firebase

Firebase is basically just an add on to your app to make it even better and relevent. Being able to incorporate authentication and a realtime database to your app makes it secure and makes it feel up-to-date. There are other things that firebase can do for you but I only dove into the realtime database as well as the authentication. However Firebase is also a platform with its own hosting capability, meaning you can launch an app straight from their platform which is so insane. This is only for web apps though but still amazing.  
For firebase the first step is to install the SDK which is also know as the Software Development Kit. The Software Development Kit is just like how it sounds. It is a kit used my software developers to 

### Authentication
Getting authentication to work on firebase is easy to learn on [Firebase intro to auth](https://firebase.google.com/docs/auth/). Being able to authenticate different users based on facebook or gmail or twitter or anything else listed in firebase is super easy. All you have to do is first find the dependencies that are required and use them with the SDK specific for whatever you are using. 
For example, authenticating using facebook  
```
dependencies{
    implementation 'com.firebaseui:firebase-ui-auth:4.0.0'  
    implementation 'com.facebook.android:facebook-android-sdk:4.x'
}
```
However for authenticating using say twitter, you would need to use a different SDK
```
dependencies {
    implementation 'com.firebaseui:firebase-ui-auth:4.0.0'  
    implementation 'com.twitter.sdk.android:twitter-core:3.x'  
}
```