The two main protocols involved in web servers are Hypertext Transfer Protocol (HTTP)
and Transmission Control Protocol (TCP). Both protocols are request-response protocols, 
meaning a client initiates requests and a server listens to the requests and provides a
response to the client. The contents of those requests and responses are defined by the
protocols.

TCP is the lower-level protocol that describes the details of how information gets from
one server to another but doesn’t specify what that information is. HTTP builds on top of
TCP by defining the contents of the requests and responses. It’s technically possible to
use HTTP with other protocols, but in the vast majority of cases, HTTP sends its data over
TCP. We’ll work with the raw bytes of TCP and HTTP requests and responses.