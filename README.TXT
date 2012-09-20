
Jetty WebSocket Example - Server and Client
-------------------------------------------

To build:

  mvn

To run server:

  mvn -Pserver exec:exec

To run client:

  mvn -Pclient exec:exec

The pom.xml file contains the property for the Jetty version (7.5.0.RC1) as well
as the arguments for the client and server execution.

The java source code is under src/main/java

The HTML, javascript and CSS is under src/main/resources

