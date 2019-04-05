## FIPS 140-2 standards

FIPS or Federal Information Protection standards 140-2 is a US government security standard used to prove cryptographic modules. It is covered under title Security requirements for cryptographic modules. Getting a FIPS 140-2 certificate assures that the product has been tested and is approved by US/Canadian governments.  It is widely accepted by other governments even though it is a US/Canadian government standard. 

FIPS 140-2 validates both hardware and software components of a cryptographic module. 

The FIPS certification standard defines 4 increasing, qualitative levels, which are very thoughtfully named: level 1, 2, 3 and 4.

```Level 1:``` Requires production grade equipment and an approved algorithm.(externally tested)

```Level 2:``` Requires the ability of temper-detection and role based authentication. Software implementation must run on OS meeting common criteria at EAL2.(Evaluation Assurance Level)

```Level 3:``` Required the device to be temper resistance and user-based authentication. There must be a logical separation between the interfaces by which CSP “critical security parameters” enter and exit the system. Like CSP needs to be encrypted before entering and leaving the system.

```Level 4:``` The system should be temper-active. In the events of an attack the system should be able to take actions to protect the CSPs. For example setting the parameters to zero.

*FIPS 140-2 allows software only implementation of level 2 and level 3(Requires a lot of standards to be followed)*

## Routing
Routing is the process of moving the packing from one host to another. Routing can either one of three types:

Static routing

Dynamic Routing

Default Routing


## Switching
Switching is the process of channeling data received from any number of input ports, to another designated port that will transmit the data to its desired destination

Circuit switching

Packet switching

Message Switching

	A switch working on message switching, first receives the whole message and buffers it until there are resources available to transfer it to the next hop.


## VLANS

A VLAN is a group of devices on one or more LANs that are configured to communicate as if they were attached to the same wire, when in fact they are located on a number of different LAN segments. Because VLANs are based on logical instead of physical connections, they are extremely flexible.

VLANs define broadcast domains in a Layer 2 network. For example if we have User A, B and C all in different networks but in the same virtual network and if A broadcasts a message it will be received by B and C even though they are not on the same network. This because they are in the same Virtual network.

## HTTPS
Hypertext Transfer Protocol Secure (HTTPS) is an extension of the Hypertext Transfer Protocol (HTTP). It is used for secure communication over a computer network, and is widely used on the Internet. In HTTPS, the communication protocol is encrypted using Transport Layer Security (TLS), or, formerly, its predecessor, Secure Sockets Layer (SSL). The protocol is therefore also often referred to as HTTP over TLS, or HTTP over SSL.

The principle of HTTPS is to authenticate the website in use and also the protection of privacy and integrity of user data over the internet. It protects against man in the middle attack and the bidirectional communication ensure that the data is safe from eavesdroppers and tempering of communication.

HTTP operates at the highest layer of the TCP/IP model, the Application layer; as does the TLS security protocol (operating as a lower sublayer of the same layer), which encrypts an HTTP message prior to transmission and decrypts a message upon arrival. Strictly speaking, HTTPS is not a separate protocol, but refers to use of ordinary HTTP over an encrypted SSL/TLS connection.


## TLS
Transport Layer Security (TLS), and its now-deprecated predecessor, Secure Sockets Layer (SSL), are cryptographic protocols designed to provide secure communication over a network. 

The TLS protocol aims primarily to provide privacy and data integrity between two or more communicating parties. When secured by TLS, connections between a client (e.g., a web browser) and a server (e.g., wikipedia.org) should have one or more of the following properties:

The connection is private (or secure) because symmetric cryptography is used to encrypt the data transmitted. The keys for this symmetric encryption are generated uniquely for each connection and are based on a shared secret that was negotiated at the start of the session.

The identity of the communicating parties can be authenticated using public-key cryptography. This authentication can be made optional, but is generally required for at least one of the parties (typically the server).

The connection is reliable because each message transmitted includes a message integrity check using a message authentication code to prevent undetected loss or alteration of the data during transmission.


## SSH
SSH provides a secure channel over an unsecured network in a client–server architecture, connecting an SSH client application with an SSH server. It was designed as a replacement for telnet which sent information in plane text(notably Password).

The encryption used by SSH is intended to provide confidentiality and integrity of data over an unsecured network.

SSH uses public-key cryptography to authenticate the remote computer and allow it to authenticate the user.


## Ipsec
 Internet Protocol Security (IPsec) is a secure network protocol suite that authenticates and encrypts the packets of data sent over an internet protocol network. It is used in virtual private networks

IPsec includes protocols for establishing mutual authentication between hosts at the beginning of a session and negotiation of cryptographic keys to use during the session.

IPsec is a layer 3 OSI model or Internet Layer end-to-end security scheme, while some other Internet security systems in widespread use operate above layer 3, such as Transport Layer Security (TLS) and Secure Shell (SSH), both of which operate at the Application layer. 


## Evaluation Assurance Level(EAL)
The Evaluation Assurance Level (EAL1 through EAL7) of an IT product or system is a numerical grade assigned following the completion of a Common Criteria security evaluation.

The seven levels of it are:- 

EAL1: Functionally Tested

EAL2: Structurally Tested

EAL3: Methodically Tested and Checked

EAL4: Methodically Designed, Tested and Reviewed

EAL5: Semiformally Designed and Tested

EAL6: Semiformally Verified Design and Tested

EAL7: Formally Verified Design and Tested