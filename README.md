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


When following along with the code to implement the access control, I ran into an issue that was not covered in the tutorial. We were trying to prevent a user from accessing the url to view the edit article page of an article authored by another user. I was receiving this error being in the node server:

"Error: Can't set headers after they are sent."

In this case it was happening because the code was sending send data more than once.

Here is a link to a stackoverflow solving this issue.

https://stackoverflow.com/questions/34983520/express-js-routing-error-cant-set-headers-after-they-are-sent
