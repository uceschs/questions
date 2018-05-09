# The Question App

Introduction –


The aim of this work is to create 2 phone apps that can make questions to the database then retrieved and answered by the user with a locational based interactive map. This work is basically form by 2 major components. Firstly, the user can login the Question App to create some interesting questions by clicking on the map and set the questions to be stored in the database for later use. Secondly, the Qiz App allows user to track their own location and get the points that includes questions near them on a map when they walk around with their phone. At the same time, they will be able to answer the question and submit the answer as well as their personal detail. Finally, a server-side file called httpServer.js is mainly serving the data and getting the data that user query or created. Also, it can help to serve on the browsers that doesn’t like an uncertified HTTPS server such as Edge.


The functionalities -

. Locate the user and has 100 meters buffer for where user is.
. Click on the map, it can show the user’s location coordinates as well as storing the coordinates for making questions.
. A box for creating the question and four boxes for storing the answers, and the correct answer will have to be ticked.
. An upload data function that can send the user’s questions, answers and the chosen latitude and longitude of the question.


Leaflet map had been used in this work.


