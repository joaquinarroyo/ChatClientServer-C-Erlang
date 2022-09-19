# Chat Client-Server 
__Authors__ [Cainelli Ignacio](https://github.com/NachoCainelli) and Arroyo Joaquin.

Implementation of a chat with the client server model in C and Erlang. The client is implemented in C, and the server in Erlang.

The server will be started with the command 
```
server: start()
```
after compiling the server module in the Erlang VM. 

The client will start with the command 
```
./cliente 127.0.0.1 [port]
``` 
(The port constant is defined with 1234), after having compiled the program with the command ```make client```
