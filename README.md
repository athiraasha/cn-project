# cn-project
CHATROOM using socket programming and tkinter
<p>Chatroom is a feature generally used in various applications which allows multiple
users to communicate and share data with each other while within a gaming
application or any other website. This feature allows users to send/receive
messages, transfer files such as audio, video etc., among users.
Our project implements this feature of exchange of messages and transfer
of files among users in a chatroom implemented with Tkinter GUI.
Firstly, a chat server is required and hence created, that responds to the
requests sent by the clients wanting to communicate. This was done using socket
programming (TCP sockets were used) and the concept of multithreading. Clients
are served by accepting new connections, broadcasting messages and handling
clients.
Next important part is a client. Client is provided with a GUI for
communication. A client would wish to send/receive messages or transfer files or
both. These functions are implemented using Tkinter modules.</p>
