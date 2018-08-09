## How The Web Works

### Background:

Review the materials below.

* First let's read [MDN HOW WEB WORKS](https://developer.mozilla.org/en-US/Learn/Common_questions/How_does_the_Internet_work)
* Next let's watch a few quick examples of [how the internet works](https://www.youtube.com/watch?v=7_LPdttKXPc).
* And [how IP addresses work](https://www.youtube.com/watch?v=KFooN7Mu0IM   - how IP addresses work).
* Finally let's tie these things together and watch a video about [DNS - what happens when you type an address into a web browser](https://www.youtube.com/watch?v=72snZctFFtA).
* Lastly, let's read a little about [the anatomy of a URL](https://doepud.co.uk/blog/anatomy-of-a-url)

### Questions:

Now we have a better grasp about the internet, and how some of the things are working. Now, let's answer a few questions to check our understanding. Don't be afraid to do additional research (googleing) for an answer. Fork this gist and answer the following questions:

1. Describe, step by step, what happens when I type `www.example.com` into my browser and try to go to the page?
My browser would look in it's cache to see if it already knows where to find this domain name, if not, it asks the OS which then asks the resolving name server. If the resolving name server has it in it's cache, great, if not, it goes to the root name server, which leads to the correct Top Level Domain server, which leads to the Authoritative Domain server which will then provide that domain name's IP address. The OS delivers this back to the browser, then the browser sends a request through it's router, and then modem, and then to the ISP for the resoucre associated with the IP address.  The ISP finds the server this IP is located on and makes the request. The request is processed and a copy of that resource is sent via packets back through the network (ISP, modem, routers) to my browser where the packets are reassembled into their original form!
1.  What does HTTP stand for?
Hypertext Transfer Protocol. Set of rules for how applications should send info and manage requests on the web.
1. 	What protocol does the World Wide Web use?
HTTP or HTTPS
1. 	Each computer on the Internet is assigned an IP address, what does IP stand for?
Internet Protocol
1. 	What does DNS stand for? A. Domain Name System
  * A. Domain Name System
  * B. Digital Number System
  * C. Domain Number System
  * D. Domain Name Service
  * E. Digital Name Service
1. 	How are text domain names matched to their respective numeric IP addresses.
See answer to first question! :) 
1. 	What is the client?  C. Software making the request.
  * A. A purchaser
  * B. Internet shopping customer (Consumer)
  * C. The software which requests information from a server (browser)
  * D. The server to which a particular computer sends data
  * E. The computer which the IP address belongs to
1. 	What does URL stand for? 
Uniform Resource Locator
1. 	What are protocols?  D. Set of rules for transferring data/documents over network.
 * A. The standardisation of IP addressess
 * B. The DNS standard method for data transfer
 * C.	The standardised network address system
 * D.	The standardised method for transferring data or documents over a network
 * E.	The standardised method for prioratising data or document storage over a network
1. What does DNS stand for?
Domain Name System
1. what is the `www` portion of a url?
This is the subdomain of the domain name, usually denotes the web server on the domain.
1. What is The markup language used for all web documents?
HTML - hypertext markup language
1. What is the organization that monitors web technologies?
W3C - World Wide Web Consortium
1. What is the Protocol for transferring web documents on the Internet?
HTTP is the IP for the web.
1. What matches the domain names with numeric IP addresses?
DNS





