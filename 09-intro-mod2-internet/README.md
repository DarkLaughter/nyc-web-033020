# Intro to Mod 2 & the Internet


## Recap Mod 1:
Some of the things we Learned last Mod
* **Ruby** - A Coding language (object oriented)
* **Objects** -  Representation of real world. (Instaances of class) 
* **Domain Modeling** - Relationship between object in a data table
* **SQL** - language to communicate with database (manipulate databse)
* **ORM** - transaltes sql into oo languages.
* **Active Record** - ORM
* **CRUD** - CREATE READ UPDATE DESTROY




## Overview Of Mod 2:
By the end of this Mod you should be able to create a fullstack web application
* HTTP 
  * Request & Response
  * REST 

* Sinatra
  * MVC
    - Models
    - Views
    - Controllers
  * ERB
  * How RESTful routes map to CRUD actions

* Rails
  * Routes 
  * Rails helpers

* HTML/CSS



## Introduction to the internet

* What is the internet?

  Internet - Hardware 
  Web - sofware


  * How is data sent over the internet?
  * TCP - Transmission Control Protocol -> how data gets sent
  * IP - Internet Protocol, IP Adress -> where
  * HTTP - HyperText Transfer Protocol - what kind of data
  * HTML - HyperText Markup Language

* How can I find out the IP address of www.google.com using a terminal command? What kind of server makes this lookup possible?
  * DNS (Domain Name System)
  * `nslookup`
  * https://iplocation.com/

  * What's the difference between static and dynamic websites? What are some of the benefits of a dynamic website?

  * https://en.wikipedia.org/wiki/ARPANET
  * https://en.wikipedia.org/wiki/Tim_Berners-Lee
  * http://info.cern.ch/hypertext/WWW/TheProject.html


* What is a server? What is a client?

* What is the request / response cycle?
  - Anatomy of Request
   - HTTP Verb (GET POST PATCH DELETE)  URL 
   - Headers 
   - Body

  - Anatomy of Response
   - Status Code
   - Headers 
   - Body
  

* With a client and server, which makes the request? Which sends the response?

* What is a HTTP request? Make a few, using at least two of these tools: Google Chrome, Postman, curl

* What are the parts of a HTTP request
  * Use a web browser to find the headers for an HTTP request. What do you think these headers do?
  * What is usually in the body of an HTTP _response_?
  * What is a HTTP status code? What do the codes 200, 404, 500, 503, 302, 422 and 418 mean?
    * https://http.cat/
  * Why do we use HTTP verbs? What is the difference between what GET, POST, PUT, PATCH, and DELETE requests do?
  * What is a URL? Which part of a URL is the scheme (protocol)? Where is the host? The port? The path? Query string?  What is the purpose of each of these parts? 
    * https://docs.google.com/presentation/d/1no3yw_Vw4hBzGDlsEDcubvFnowi-Exjg9FW_VJid_U0/edit#slide=id.g378a2b8862_0_5


https://www.google.com/search?
q => cute+doggos
oq => cute+doggos
aqs => chrome..69i57j0l7.2553j0j7
sourceid => chrome
ie => UTF-8


## Intro to Sinatra
* Build a basic web app in 30 seconds
* Do basic web requests in Sinatra
* Explain what Sinatra is


--------------------------------------------------------------------

* Walk through `corneal new`
* Talk about `shotgun`
* Walk through Sinatra basic file structure
* Walk through Model View Controller \(MVC\) pattern and give an example
  * https://docs.google.com/presentation/d/1no3yw_Vw4hBzGDlsEDcubvFnowi-Exjg9FW_VJid_U0/edit#slide=id.g378a2b8862_0_22
* Explain how web frameworks \(like Sinatra\) use the MVC pattern and why