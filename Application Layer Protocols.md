Application Layer Protocols:

Commonly used application layer protocols:

Some of the most commonly used application layer protocols are:
    • DNS
    • HTTPS
    • FTP
    • SMTP,POP


HTTP:

    • HyperText Transfer Protocol
    • Uses port 80
    • Widely used to transfer web pages using the World Wide Web(WWW)
    • Not reliable by itself but uses Transmission Control Protocol(TCP) to achieve reliability
    • In-band protocol. Commands and data travel from the same port
    • Stateless protocol. Does not store metadata because of the volume of requests sent over http. However companies can and do use cookies to store metadata.
    • HTTP 1.0 non-persistent: Creates new connections for every request. Loses connection as soon as session is closed/ended.
    • HTTP 1.1 persistent: Connection remains active even after session is closed unless the connection is explicitly ended.
    • Common commands are: 
            ▪ head(retrieves metadata about the page)
            ▪ get(to access/request the page/resource/document from the server)
            ▪ post(to send information from client to server such as when filling a form)
            ▪ put(to send document from server to client)
            ▪ delete(to delete information)
            ▪ connect(to establish a connection with server)

HTTPS works on the secure socket layer. In an HTTPS sessions, requests are authenticated every time to prevent malicious access


FTP:

    • File transfer protocol. 
    • Used to share files over the network
    • Uses port 21 for control commands and port 20 to send data. Not an in-band protocol.
    • Control connection is persistent while the data connection is non-persistent.
    • Provides reliability by utilising TCP.
    • Stateful protocol. Stores metadata about every file transfer.
    • Synchronous protocol. If a file is being transferred between two users, both of them need to be online/ active.



SMTP & POP:

    • Simple Mail Transfer Protocol & Post Office Protocol
    • SMTP and POP are used for email transfer, by every company providing email services.
    • SMTP is used to push email and POP is used to pop or retrieve email.
    • SMTP is asynchronous. An email can be sent anytime and the recipient can check it and respond whenever they connect to the network.
    • SMTP uses port 25. POP uses port 110 to connect without encryption and port 995 to establish a secure connection.
    • SMTP pushes email from a Mail Client to a Mail Transfer Agent and from there to another Mail Server/ Mail Transfer Agent. POP retrieves email from the Mail Transfer Agent and sends it to the Mail Client.
    • Multipurpose Internet Mail Extensions(MIME) protocol is used to send images, videos and other multimedia.
