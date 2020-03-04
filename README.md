## What is a web service?
Web services allow different system to talk to each other and share data over the internet. These system can be a combination of different devices or applications

**Popular tools:**
- Postman
- SoapUI
- GraphQL

**Two main types of web services:** 
- SOAP (Simple Object Access Protocol):
  - sends messages using SML
  - XML document is sent with data
- RESTful
  - uses HTTP to access resources

**Advantages**
1. Reusability
2. Language Transparency
3. Usability
4. Deployability

**Need to watch out for**
- Latency: The time it takes a request to return a response
- Partial failure: when a server or network fails to respond (The more web services used in a single application, the bigger the risk of experiencing a partial failure)

**How does a web service security works?**
- Authentication: validates identity of client
  - Basic Authentication (Basic Auth): 
    - The simplest protocol available for performing web service authentication over the HTTP protocol
    - Only ask for username and password and converts to a single base-64 encoded value and pass it along in the authentication HTTP header
  - API Key Authentication
    - requires the API to be accessed with a unique key 
- Authorization: determines level of client's access
- Not Authorized will return a 401 code

Web Services
- Dependent on SOAP protocol
- requires more work to pack and unpack data
- All web services are APIs

API
- light weight and good for mobile devices
- not all API are web services

Micro-services
- fully contained individual components that communicate with each other in calling clients

**How to decide which one to use?**
- The business problem you're trying to solve
- The type of application you're trying to build
- The capabilities of your calling clients

**REST** (Representational State Transfer) API:
A set of guidelines used to design APIs

Four Principles
1. Uniform resource Identifier (URI)
2. Operations
  - GET- retrieves a resource
  - POST - creates a resource
  - PUT - updates a resource
  - DELETE - removes a resource
3. Formats 
    - HTML
    - XML
    - Plain Text 
4. Stateless
   - Server will not store any state the client made 

**Payload**: Data sent between client and server

RESTful APIs : can use XML, JSON and something else entirely
SOAP based web services: only allows XML

HATEOAS (Hypermedia As The Engine Of Application State):  
- it specifies that RESTful APIs should provide enough information to the client to interact with the server
- client interacts with a REST API entirely through the responses by the server

HETEAOS Principle
- Resources should be discoverable through the publication of links





   



