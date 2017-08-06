NOTES:

Using the MongoDB shell is very useful for getting fluent with working with the database.

To get started make sure you have mongod running. Then you can run the mongo.exe file which is in the mongodb directory where it is installed.

example path: /usr/local/opt/mongodb/bin

-Use the 'cls' command to clear the screen.
-'show dbs' will list the databases
-'use <NAME OF DATABASE>' will create the database and also switch to that db.
-'db.createCollection(""<NAME OF COLLECTION>")' will create a collection within the database.
-'db.<NAME OF COLLECTION>.insert(<OBJECT)' will create an entry into the collection.
-'db.<NAME OF COLLECTION>.find()' will list all entries in a specified collection.
-'db.<NAME OF COLLECTION>.find().pretty()' will list the entries with line breaks.
