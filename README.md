### Understanding subscriber and message broker.
1. what is amqp? <br>
   Advanced Message Queuing Protocol (amqp) is an open standard messaging protocol designed
   for message-oriented middleware. AMQP enables different applications or components to communicate
   with each other over a network, reliably and asynchronously, by exchanging messages. It
   provides features such as message queuing, routing, reliability, and security. AMQP is widely
   used in distributed systems, particularly in scenarios where reliable message delivery and
   communication between different parts of a system are crucial. <br><br>
2. what it means? guest:guest@localhost:5672 , what is the first quest, and what is the second
   guest, and what is localhost:5672 is for? <br>
   guest:guest represents the username and password used for authentication. In this case,
   both the username and password are "guest". @localhost:5672 specifies the hostname and port
   number of the AMQP broker. "localhost" indicates that the broker is running on the same machine
   as the client. The default port for AMQP is 5672. <br><br>
   The full connection string guest:guest@localhost:5672 is telling the client to connect to the
   AMQP broker with the username and password "guest" running on the local machine (localhost) on port 5672.

### Simulation slow subscriber
![img.png](img.png)

### Running at least three subscribers
![img_1.png](img_1.png) <br>