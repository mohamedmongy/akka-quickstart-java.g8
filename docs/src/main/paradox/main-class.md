## The Main class
 
The `Main` class in Hello World creates and controls the actors. Notice the use of an `ActorSystem` as a container and the `actorOf` method to create the Actors. Finally, the class creates the messages to send to the Actors.
 
@@snip [AkkaQuickstart.java]($g8src$/java/com/lightbend/akka/sample/AkkaQuickstart.java)
 
Similarly, let's look again at the full source code that defines the Actors and the Messages they accept.

