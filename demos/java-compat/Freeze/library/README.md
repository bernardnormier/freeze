This example demonstrates the use of Freeze to manage books in a
library.

To run the demo, first start the server:

$ java -jar build/libs/server.jar

In another window, populate the server's database by starting the
client and redirecting its input from the file "books":

$ java -jar build/libs/client.jar < books

Then start the client again to use the demo interactively:

$ java -jar build/libs/client.jar

Type "help" to get a list of valid commands.

The collocated executable combines the client and server into one
program. In this case you do not need to start a separate server.
If you have not already populated the database, you can do so using
the collocated executable as shown below:

$ java -jar build/libs/collocated.jar < books

Then start the interactive demo like this:

$ java -jar build/libs/collocated.jar
