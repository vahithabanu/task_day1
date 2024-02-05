
Blog on difference between HTTP 1.1 and HTTP 2:

What is HTTP 1.1?

     The Hypertext Transfer Protocol, or HTTP, is an application protocol that has standard for communication on the World Wide Web .
     HTTP/1.1 loads resources one after the other, so if one resource cannot be loaded, it blocks all the other resources behind it.
     It allowed multiple requests and responses to be sent over a single connection.
	

What is HTTP 2?

    HTTP/2 makes web pages load faster and more efficiently by streamlining communication between the browser and server.
    HTTP/2 is able to use a single TCP connection to send multiple streams of data at once so that no one resource blocks any other resource.

Difference between HTTP 1.1 and HTTP 2:

HTTP 1.1:

It works on the textual format.
There is head of line blocking that blocks all the requests behind it until it doesn’t get its all resources.
It uses requests resource Inlining for use getting multiple pages.
It compresses data by itself.

HTTP 2:

It works on the binary protocol.
It allows multiplexing so one TCP connection is required for multiple request.
It uses PUSH frame by server that collects all multiple pages .
It uses HPACK for data compression.


Methods used in HTTP 1.1:

Connect, Head, Options, Delete, Post, Trace, Get, Put, Patch.
Methods used in HTTP 2:

Binary, Header Compression, An updates protocol stack, Multiplexing, Stream prioritization, Encryption, HTTP/2 server push, Connect, Security.

Advantages of HTTP 1.1:

Improved performance over HTTP 1.0 due to the introduction of persistent connections, caching, and support for chunked encoding.

Disadvantage of HTTP 1.1:

Still relatively slow compared to modern web applications.
Limited support for server push, header compression, and pipelining.

Advantages of HTTP 2:

Significant improvement in performance over previous versions of HTTP due to multiplexing, server push, binary framing, and other enhancements.

Disadvantages of HTTP 2:

Limited adoption and support, especially among older web browsers and servers





                     


