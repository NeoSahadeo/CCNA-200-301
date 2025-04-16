Main purpose of the chapter is to provide an idea of what TCP/IP is.

## History
- ISO created a model called OSI (Open Systems Interconnection)
- Department of Defence Created the TCP/IP model
- Companies were using both but by end of the 1990s TCP/IP was the dominant standard model

## Overview
The TCP/IP is defined in a document called [[TCP-IP RFC]]
TCP/IP is a networking model and the network model is represented into layers that each build of the one below.

![[Pasted image 20250416210103.png]]

![[Pasted image 20250416210240.png]]

- **Same Layer Interactions** - Are 'two' computers communicating with each-other using the same layer. The header contains what the computer wants to do.
- **Adjacent Layer Interactions** - Are different layers on a single communicate with each-other where the layer below provides a service to the layer above it.

> Protocol Data Unit (PDU) is used to define any message defined by a protocol

*Segments*, *Packets*, and *frames* are talk about different layers in the TCP/IP model. Where segments refer to TCP, packets to IP and ethernet to frames.

(de-)Encapsulation is the process of adding or removing bits the the front (with the exception of the ethernet frame which has a trailing bits called "Link Trailer").

Even though virtually every computer in the world implements TCP/IP, the OSI model is still used to describe networking models.

The Difference Between TCP/IP and OSI![[Pasted image 20250416220451.png]]

The Encapsulation Process
![[Pasted image 20250416220609.png]]