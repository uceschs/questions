# The Question App

The aim of this work is to create 2 Andriod based phone apps that can make questions to the database then retrieved and answered by the user with a locational based interactive map. This work is basically form by 2 major components. Firstly, the user can login the Question App to create some interesting questions by clicking on the map and set the questions to be stored in the database for later use. Secondly, the Qiz App allows user to track their own location and get the points that includes questions near them on a map when they walk around with their phone. At the same time, they will be able to answer the question and submit the answer as well as their personal detail. Finally, a server-side file called httpServer.js is mainly serving the data and getting the data that user query or created. Also, it can help to serve on the browsers that doesn’t like an uncertified HTTPS server such as Edge.


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development or testing purposes. See deployment for notes on how to deploy this work on a live system.


### Prerequisites

What things you need to install before install the app and how to install them

```
- VPN connection to the school server
   * Download on your android phone and input password, keep it running on the background

- Connection to Phonegap server
   * Download phonegap app to your android phone and connect with your phonegap IP address
   
- Connection of httpServer.js
   * Will need to be run on the laptop first

```

### Functionality 

```
. Locate the user and has 100 meters buffer for where user is.
. Click on the map, it can show the user’s location coordinates as well as storing the coordinates for making questions.
. A box for creating the question and four boxes for storing the answers, and the correct answer will have to be ticked.
. An upload data function that can send the user’s questions, answers and the chosen latitude and longitude of the question.
```



