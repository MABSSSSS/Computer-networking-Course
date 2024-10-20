
**COMPUTER NETWORKING COURSE:**

computer connected together is network .
networking of these computers is internet.


A-----B_-_-_-_>


*How did it start?*

ARPA (advanced Research project Agency)


TCP(Transmission Control protocol)/IP(Internet protocol):

(WWW)
all owing you to access all these documents and the data
World wide web is project which store these documents.


Protocols: are rules defined by internet socity how data trasnfers.
**internet society**
RFC (Request for comments)

Client and server:

client request server and server reponse back to clients(google.com)...


TCP: data will reach destination and it not be corrupted.
UDP:User datagram protocol 
HTTP: used by WWW (hyper text transfer protocol). between client and servers all in http .

data you will be getting packets. individual calls in response of packets.

All servers,PC identified as IP addresses.

command( curl if config.me -s) for getting IP address of mine PC.

ISP(internet service provider)--->Router/modem--->Global IP address (IP1,IP2,IP3     are local IP addresses).

Modem assign using DHCP .
Router will decide the requester.

IP address to decide which device to send data.

when two freinds talking to each other , they have IP address(computer addressing) and port number (application address).


All HTTP step happens on port 80
total =2^16=65000

0-1023  reserved ports.

1024-49152(application regisered ports)

SQL =1433 port

remaining one: we can use.

Two PC connected to ISP then to Internet .

if 1mbps(mega bits per second ).
1mbps = 100000 bits/second.

1gbps =10^9 bits/second.
1kbps =1000 bits/second.

when you are sending data then it is uploading .
when we recieving data it is downloading data


Two Way of communication between PC:
guided and unguided way.

e.g:submarinecable.com

Physically: connected(Optical fibre cables, co-axial cables)
wireless:  bluetooth, wifi, 5G

cables are faster then satellites.


*LAN(Local Area Network):    small house/offices.*

connected by ethernet cables , wifi .

--- MAN(Metropolitan Area Network)  acrossa city

--- WAN(wide area network): Access countries(optical fibre cables).

1. sonet(synchronous optical network) it carries the data and it cover the larger distances.
2. frame delay.

___Modem used to convert digital signals into analog signals.
___Router that routes the data pocket based on their IP addressess.


ISP connected to large service provider.

Topology: 

1. bus topology: only one person can send data throught th e cable netwroking.

2. Ring: PC connected by ring.
every sytem communicates with one another.

alot of unnnecesary calls have been made.

3. star : one controlling device which is connected to all the PC.

4. Tree topology: combination of bus and star .

5. Mesh : every single PC connected to every single PC.

expensive(so much wiring used).
scalability issue .


**Structure of network:**
Order---Restaurant---delivery company(PK)-->Transported--->UAE--->delivery company repsonsible--->Amazon-->Order recieving.

Order to recived is application layer:

OSI Model:(open system interconnection model)

standard way of communicating of two PC.

___seven layers in OSI model:

1. Application layer.-->implemented in software
2. Presentation layer.
3. Session layer(managing connection)
4. Transport layer.(transportation)
5. Network layer.(logical addrresing)
6. Datalink layer.(logical and ) subnet mask and ip called packet.
7. Physical layer.(convert bit singals to digital or electrical signals).

___UDP(Connectionless)
___TCP(connection and no data loss).
MAC(Media access control).
SSL(secure socket protocol) for encryption and decryption:

A---P--S---T--(packets and segments)---N(assign ip )---PL---Physical router of your network.

Another Model(TCP/IP Model):
 more practically based.

Application
Transport
Network
Datalink
Physical

1. Application Layer:

---where users interact with this.
---whatsapp, browser etc...
---where on your device

 has some protocols.(rules and regulation for communications)
 client server architecture.

Server is webiste that is hosting like google.

Collection of server in a big company is known as server.

1. (~ping goggle.com)

google have many servers.

measures round trip time for messages send from orginating host to send back to computer is ping time.

1. Clinet server.
2. Peer to peer.
 many computers are connected to one another.
 scale it very rapidly and decentralised network .

 1. Repeater: is ath ephysical layer .. generate the signal over the same network.
 2. port device.
 Hub: multiple repeater. connects multiple wires coming from different braches . it cant filter data.
 types of hub:
 Active hub:
 Passive hub:

3. Bridge: operates at data link layer.
transparent and source routing badges.
4. Switches: mutliport bridge with buffer and design that can boost its efficency  and performance. data link layer device.
switch divide collision domain of hosts but broadcost domain remain same.

5. Routers:
 routes data packets based on their IP addresses .Network layer device.
 It normally connects LANS and WANS together and have dynamically updating routing tables based on which they make decissions on routuing data packets.
 6. Gateway:
 passage tpo connect two netwrks together . 
 7. Brouter : bridge and routewr combines .


 **PROTOCOLS:**

 web protocols: 
 ___TCP/IP: 
 http (hyper text transfer protocols)
 DHCP
 FTP(File transfer protocols)
 SMTP(Simple mail transfer protocol)
 POP3(recieve protocols) and IMAC for recieve protocols.
SSH
VNC(Virtual network)
 
 Telnet(enable users to connect to remote server by telnet).port :23
 it is not encoded and decoded.

 UDP: stateless connection (data may be loss during the connection).

 Porgram can have many processes 
 Thread is lighter version of processes.

Sockets: (interface between process and internet)

need to send messages from one system to another system.

Ports: which app we are working with ..

Ephermeral ports(randomly assign ports number)
 exist on the client side but on server side you have to know the port first.


___HTTP:__
get,push,post and head.

UDP in vedio conferencing
HTTP(stateless) user TCP(all data is recived in state) in transport layer
HTTP in application  layer

HTTP Methods:
1. Get(requesting data)
2. POST(posting data)
3. PUT(puts data at specific location)
4. DELETE

Status code: 
100:informational categories code.
200: success codes
300: redirecting codes
400: client error
500: server error

Cookies: is unique string

 stored on client browser.
 user value is cookie.

 Also cookie have expiration date.


---Third party cookies:
set for the urls that we didnt visits.

How email works:?
will use TCP
for sending email SMTP , POP3 .


sender --->Sender's SMTP server--->Reciever SMTP server--->Receiver

POP(Post office protocol)  --->port:110

client--(Authorize and transact)--->pop server

IMAP(Internet message Access Protocol):
local copies available on various devices.
subject,headers and body...


__DNS:(Domain Name system)__

are mapped to two ip addressses.
use DNS to find IP addresses of google.

Directly data base service.

mail.google.com

mail: is sub domain 
google: is second level domain 
com: top level domain

__Root DNS Servers:__

they have thier top level domains 
.io , .org and .com


--->e.g:(root-servers.org)

check in own computer--->ISP---_.com--->root server and TLD(-->it will give you IP address).

Then ISP connect to the server of google.com

cant buy a domain name only can we rent it .

command  ---(dig goggle.com)
domain information groper...


2. Transport Layer:

the transportation part is done by transport layer.
it take information from the network to the application.

transport has some protocols
TCP(100 data sent)
UDP(data loss in sent)


multiplexing (allows things to alot of destinations just by one medium)

sockets (which have port numbers)

then to demultiplexer:(message,file and VC)

data travels in packets.--->transport layer will attach these socket port numbers.

__Transport Layer__ also takes care of congestion control.

__Congestion control algorithms built in TCP.__

__CheckSums:__

computer sending data to your freinds (using data to check some value which is called check data).

__TIMERS:__

You are sending data packets to your friends also you (start the timer).
Friend I got it .
when you recive back timer ends.
when again sends timer started and then again ends when we recieve back.


to solve duplicate problem we use sequence numbers.


__UDP(User datagram protocol):__
it is TLP .
fro network to transport layer and then again back to network layer.

Data may or may not be delivered.
Data may changed on the way.
Data may not be in order.

---basically it is connectionless protocols.

UDP uses Checksums .

UDP Packet:
Every data packet will have source port number.


source port number , destination port number  , length of datagram and check sum  Also included Data.


Total size = 2^16

header (8 bytes)--some thing attached to you.

__Use cases :
It is very fast.
vedio conferencing apps.
DNS--> UDP
Gaming uses UDP.


__TCP (transmission control protocol):__
http
data stays with it.

transport layer protocols.
Application layer sends alots of raw data.

TCP segments this data--> divided in chunks, add headers .
It may also collect the data network layer.--> CHeck vedio chunks

Congestion controls.

takes care of two things:

when data doesnot arrive.
maintains the order of data.

__FEATURES:__
connection oriented.
Error control.
congestion control.
bidirectional(full duplex).

you can send both files simultaneously.

1 TCP connection between two computers.


3-way handshake:

client ----syn flag---(sequence:32)--->Acknowledgements(56)
---(sequence number)--->(ACK)---(sequence:33)--->Acknowledgement(57).


**Network Layer:**

Transport (segments).
Netwrok(packets).
Datalink (frames).


Here we work with routers:

hop-by-hop(hoping by computers until it reaches its destination).

forwarding table(data structures) comes insdie routing tables.

every device has its own address.

192.168.2 is network address.
.30 is device address.

this is how routing take places.

control plane created these tables.

CONTROL PLANE:
 
 routers --(nodes of graph)
 Edges---(links)

 two types of routing:

 1. static routing:
 manually adding all routes.
2. Dynamic routing:
   change in network it will change accordingly.


__Internet protocols IP:__
lies in networking layers.
these are known as IP hosts.

IP V4: 32 bit , 4-words
IP V6: 128 bits 

Hoping things happen over Internet Service providers.
blocks of IP addresses.

Class(range) of IP Addresses:

A  0.0.0.0
B  128.0.0.0
C  192.0.0.0
D  224.0.0.0
E   240.0.0.0 


subnet masking:
able to tell which particularly category it belongs too.

variable length.
























































































































































































































































































































































































































