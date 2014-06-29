#Dropbox Webhooks Java

This is a Dropbox application which lets you automatically scale down image files put in the dropbox app folder.

##To Run

### Prerequisites

-  You'll need JDK 8 to run this, as it makes use of lambdas in Java.
-  You'll also need Play framework 2.x . Please note that, I've tested with Play 2.3.0 only.
-  You'll need a valid Redis installation to store the user ids and cursors.

### Running locally

-  If running locally please set redis.uri suitably in the application.conf file.
-  Next go to your local checked out directory and run ``activator run``.

### Running on Heroku

-  Please follow the instructions at [Play Documentation site](http://www.playframework.com/documentation/2.3.0/ProductionHeroku) for details.

### See it running 

You can take it for a spin [here](https://whispering-everglades-1877.herokuapp.com).
