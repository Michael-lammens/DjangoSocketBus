# DjangoWebsocket
Simple demo of websockets using Django Channels. Good practices and possible variations of implementation.
- Highlights real time communication over HTTP sockets
- Notifications for messages Delivered and Read
- Message cards, show sample of chat with the last sent/received message prior to opening the chat

Portable version:

Portable directory shows an implementation using Django Rest Framework. 
- Allows us to make websocket connections using dynamic endpoints
- This version is great when message interfaces are not static
    - Ex: Site allows for sending of message from different entry points
    - Message interface follows users through seperate pages
