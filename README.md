# VoIP Client/Server
This is a client/server application written in Java to allow a basic VoIP connection.
Clients connect to the server, the server connects every client so that they can speak to each other.

##Dependencies
- [Netty 5.0](http://netty.io)
- [slf4j 1.17.12](http://www.slf4j.org/)
- [slf4j-simple 1.17.12](http://www.slf4j.org/) (recommended)

Note: You will need to use Apache Maven to download the dependencies.
This is a simple/client server for VoIP. Currently using TCP for a better sounding experience however UDP is recommended. 

##TODO:
- Packet checking/filtering

##Optional TODOs:
- Add a GUI for the client
- Account creation and private chatting/individual lobbies etc.