                                                                  HTTP 

 Http/1.1: 
The Hypertext Transfer Protocol, or HTTP, is an application protocol that has been the de facto standard for communication 
since its invention in 1989
Developed by Timothy Berners - Lee as a communication standared for www(World wide Wed)
Is a top-level application protocol that exchanges information between a client and local (or) remote web browser
From the release of HTTP/1.1 in 1997 until recently, there have been few revisions to the protocol. 
But in 2015, a reimagined version called HTTP/2 came into use, 

Http /2:
HTTP/2 began as the SPDY protocol, developed primarily at Google with the intention of reducing web page load latency by using techniques such as compression, multiplexing, 
and prioritization.
This protocol served as a template for HTTP/2 when the Hypertext Transfer Protocol working group httpbis of the IETF (Internet Engineering Task Force) put the standard together, culminating in the publication of HTTP/2 in May 2015. 
From the beginning, many browsers supported this standardization effort, including Chrome, Opera, Internet Explorer, and Safari. 
Due in part to this browser support, there has been a significant adoption rate of the protocol since 2015, with especially high rates among new sites.
which offered several methods to decrease latency, especially when dealing with mobile platforms and server-intensive graphics and videos. 
HTTP/2 has since become increasingly popular, with some estimates suggesting that around a third of all websites in the world support it. 
In this changing landscape, web developers can benefit from understanding the technical differences between HTTP/1.1 and HTTP/2, 
allowing them to make informed and efficient decisions about evolving best practices.

                                                  DIFFERENT BETWEEN HTTP/1.1 AND HTTP/2

1. HTTP/1.1 and HTTP/2 is the binary framing layer, which can be thought of as a part of the application layer in the internet protocol stack. As opposed to HTTP/1.1, which keeps all requests and responses in plain text format, HTTP/2 uses the binary framing layer to encapsulate all messages in binary format, while still maintaining HTTP semantics, such as verbs, methods, and headers
2. The conversion of messages into binary allows HTTP/2 to try new approaches to data delivery not available in HTTP/1.1
3. But while HTTP/1.1 transfers these in plain-text messages, HTTP/2 encodes these into binary, allowing for significantly different delivery model possibilities
