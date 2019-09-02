# Sending Data Between Clients and Server Using Socket and Threading

These are python scripts for a server and a client.

1. The SERVER script accepts or listens to new connections and also listens for data being sent from clients.

2. The CLIENT script can be instantiated multiple times to simulate multiple client connections.

Socket was used to provide a channel and connect clients to the server thru a custom IP address and a custom port number.
*** Just make sure the host/port number of the server is the same with the client host/port number to enable proper connection.

# To run server:
python server.py

# To run client:
python client.py

*** Run server first, then client.

