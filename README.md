# UDP ping pong application.
An application to test UDP server and client interaction.

## How to run
Compile the server and client application as below.
Before compiling, modify the udp-client.c with relevant server details such as
IP and port.
```
    gcc udp-server.c -o server
    gcc udp-client.c -o client
```

Run the server in the server terminal.
```
    ./server
```

Run the client on the client machine terminal
```
    ./client
```
