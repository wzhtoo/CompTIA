# 10_DataCommunication

[10_DataCommunication &#128279;](https://alison.com/topic/learn/145594/data-communication)

## Components of Data Communication

The five most essential factors come to mind whenever we discuss network-based communication between two computing devices. The sender, receiver, mode of communication, the intended recipient, and a set of guidelines known as protocols that must be followed during communication are among them. The transmission media is another name for the communication medium. The following five elements make up data communication:

- [ ] **Sender**
  - A computer or other device that can send data via a network is referred to as a sender. It could be a laptop, smartphone, smartwatch, walkie-talkie, video camera, etc.
- [ ] Receiver
  - A computer or other device that can receive data from a network is referred to as a receiver. Any computer, printer, laptop, smartphone, television, etc. can be used. The sender and receiver in computer communication are referred to as nodes in a network.
- [ ] Message
  - This is the data or information that the sender and the receiver must exchange. Text, numbers, images, audio, video, and other types of multimedia can all be used to send messages.
- [ ] Communication Media
  - This is the channel that a message takes to go from its sender to its recipient. It can be wireless or wired and is also referred to as a medium or link. For instance, microwaves, satellite links, ethernet cables, television and phone cables, etc.
- [ ] Protocols
  - Protocols are a set of guidelines that communicating parties must abide by in order to have successful and dependable data transmission. You have already encountered protocols like HTTP and Ethernet.

# Circuit and Packet Switching

![](https://courseware-assets.alison.com/public/published/14861/images/16811047601428190009.jpeg)

Based on the theory of how the communications circuit is constructed between the communicating devices, we can categorize data connections over a telecommunications network. Three different types of circuits can be used to transmit data via the telecommunications network:

- **Leased or dedicated:** The monthly cost of a leased line is fixed and is based on the connection's capacity and length.
- **Packet-switched:** Depending on the interface data rate, the cost is frequently fixed. The cost in some packet-switched networks may vary with the volume of data being transferred. Other factors that affect price may be outlined in agreements with service providers, such as average or maximum data rates.
- **Circuit-switched or dial-up:** The price of switched service varies with the amount of time, data rate, and distance used.

# Data Communication Protocol

A collection of uniform guidelines that all communicating parties—the sender, the receiver, and any other intermediary devices—must abide by is known as a protocol. We are aware that the transmitter and receiver may be situated in several networks in various geographical regions. Additionally, since different networks' data transfer rates can differ, data must be provided in a variety of forms.

- The method through which machines on a network identify one another.
- The format in which the data ought to be changed for transmission.
- The method for determining if the data received is for that node or should be passed to another node.
- Ensuring that no data was lost during the transfer process.
- How the packets should be rearranged and handled at the destination.

It becomes difficult to ensure that communicating parties respect the rules if all the rules or protocols of a communication network are defined in one location.

# Communication Protocols

Hyper Text Transfer Protocol
HTTP stands for Hyper Text Transfer Protocol. It is the primary protocol used to access the World Wide

Web. HTTP is a request-response (also called client-server) protocol that runs over TCP. The common use of HTTP is between a web browser (client) and a web server (server). HTTP facilitates access to hypertext from the World Wide Web by defining how information is formatted and transmitted, and how the Web servers and browsers should respond to various commands.

A web page is written using a markup language like HTML and is stored on a web server for access via its URL. Once a user opens a web browser and types in the URL of the intended web page, a logical communication link between the user machine (client) and the web server is created using HTTP.

# File Transfer Protocol

File Transfer Protocol (FTP) is the protocol used for transferring files from one machine to another. Like HTTP, FTP also works on a client-server model.

When a user requests a file transfer with another system, FTP sets up a connection between the two nodes for accessing the file. Optionally, the user can authenticate using the user ID and password. The user then specifies the file name and location of the desired file. After that, another connection sets up and the file transfer happens directly between the two machines. However, some servers provide FTP logins without authentication for accessing files.

- Use of different conventions while naming files.
- Representation of text and data in different formats.
- Having different directory structures.

# Point-to-Point Protocol

PPP is a communication protocol that establishes a dedicated and direct connection between two communicating devices. This protocol defines how two devices will authenticate each other and establish a direct link between them to exchange data.

The communicating devices should have duplex modes for using this protocol. This protocol maintains data integrity ensuring that the packets arrive in order. It intimates the sender about damaged or lost packets and asks to resend them.

# Simple Mail Transfer Protocol

SMTP is a protocol used for email services. It uses information written on the message header (like an envelope on a letter sent by post) and is not concerned with the content of the email message. Each email header contains the email addresses of recipients.

When the SMTP sender successfully delivers a particular mail to one or more destinations, it removes the corresponding receiver’s email address from the mail’s destination list. When that mail is delivered to all the recipients, it is removed from the outgoing queue. The SMTP receiver program accepts each mail that has arrived and places it in the appropriate user mailbox.

# Transfer Control Protocol

TCP/IP stands for Transmission Control Protocol/ Internet Protocol. It is a set of standardized rules that uses a client-server model of communication in which a user or machine (a client) requests a service from a server in the network.

The IP protocol ensures that each computer or node connected to the Internet is assigned an IP address, which is used to identify each node independently. It can be considered to be the adhesive that holds the whole Internet together. TCP ensures that the message or data is broken into smaller chunks, called IP packets. Each of these packets is routed (transmitted) through the internet, along a path from one router to the next, until it reaches the specified destination.

# LANs

![](https://courseware-assets.alison.com/public/published/14861/images/1681105388146400397.jpeg)

Inside a building or business, high-data-rate communications are required; to meet these needs, local data communications networks, or LANs, are constructed.

LANs offer high-data-rate communications, for instance, between computers inside a single building. Only short distances are permitted due to the high transmission bandwidth (10 Mbps or above). A couple of hundred meters is the normal maximum transmission distance.

A wide-area corporate network can be created by connecting several local area networks (LANs) together with the use of switching devices (switches or bridges) or routers. With the aid of a local hardware address that is kept in the interface unit of each computer, the bridges or switches connect several LAN segments and switch frames from one segment to another.

# Internet and Its Protocol

The TCP/IP protocol suite is used by the Internet, a system of globally interconnected computer networks, to interact with one another.

Data packets are addressed and routed using a protocol, or set of rules, called the Internet Protocol (IP), so they can travel between networks and arrive at their destination. For transmission, the Internet breaks data into smaller pieces known as packets. Routers can send packets to the correct destination since each packet carries IP information. Data is sent to the correct location as packets are sent to the IP address associated with it because every device or domain that connects to the Internet is assigned an IP address.

![](https://courseware-assets.alison.com/public/published/14861/images/1681105556260993365.jpeg)
