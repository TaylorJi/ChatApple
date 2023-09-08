# 🍎Chatapple
<p>Basic messsaging app that users can send and receive messages.</p>

<p align="left">
  <img width="476" src="https://github.com/TaylorJi/ChatApple/assets/112731523/609dd7bb-ddbf-4dd1-9274-c560a6307b32" alt="Start page" >
</p>

<p align="left">
  <img width="476" src="https://github.com/TaylorJi/ChatApple/assets/112731523/758e3f03-5b9f-4385-a41f-203dd5c46d43" alt="Register page" >
</p>

<p align="left">
  <img width="476" src="https://github.com/TaylorJi/ChatApple/assets/112731523/1fbca869-1cc5-43a9-bb9a-336e21246eba" alt="Login page" >
</p>

<p align="left">
  <img width="476" src="https://github.com/TaylorJi/ChatApple/assets/112731523/8c12618d-cd18-4998-a13c-799615f0515b" alt="Logged in with user1" >
</p>

<p align="left">
  <img width="476" src="https://github.com/TaylorJi/ChatApple/assets/112731523/5fad61a8-0139-442b-abd5-ac3e510db936" alt="Logged in with user2" >
</p>





![App Brewery Banner](Documentation/AppBreweryBanner.png)

# Flash-Chat

## Our Goal

One of the most fundamental component of modern iOS apps is the Table View. Table Views are used everywhere from the Mail app to the Messages app. It’s a crucial part of every iOS developer’s tool belt. In this tutorial we’ll be getting to grips with Table Views, creating custom cells, and making our own cloud-based backend database. It’s going to be epic, so buckle up.

## What you will create

Flash Chat is an internet based messaging app similar to WhatsApp, the popular messaging app that was bought by Facebook for $22 billion. We will be using a service called Firebase Firestore as a backend database to store and retrieve our messages from the cloud. 

## What you will learn

* How to integrate third party libraries in your app using Cocoapods and Swift Package Manager.
* How to store data in the cloud using Firebase Firestore.
* How to query and sort the Firebase database.
* How to use Firebase for user authentication, registration and login.
* How to work with UITableViews and how to set their data sources and delegates.
* How to create custom views using .xib files to modify native design components.
* How to embed View Controllers in a Navigation Controller and understand the navigation stack.
* How to create a constants file and use static properties to store Strings and other constants.
* Learn about Swift loops and create animations using loops.
* Learn about the App Lifecycle and how to use viewWillAppear or viewWillDisappear.
* How to create direct Segues for navigation.


# Constants
```
struct K {
    static let cellIdentifier = "ReusableCell"
    static let cellNibName = "MessageCell"
    static let registerSegue = "RegisterToChat"
    static let loginSegue = "LoginToChat"
    
    struct BrandColors {
        static let purple = "BrandPurple"
        static let lightPurple = "BrandLightPurple"
        static let blue = "BrandBlue"
        static let lighBlue = "BrandLightBlue"
    }
    
    struct FStore {
        static let collectionName = "messages"
        static let senderField = "sender"
        static let bodyField = "body"
        static let dateField = "date"
    }
}

```

>This is a companion project to The App Brewery's Complete App Developement Bootcamp, check out the full course at [www.appbrewery.co](https://www.appbrewery.co/)

![End Banner](Documentation/readme-end-banner.png)
