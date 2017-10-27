# Hypertext Transfer Protocol -- HTTP/1.1

## Common definitions

The Hypertext Transfer Protocol (HTTP) is an application-level
 protocol for distributed, collaborative, hypermedia information
 systems. It is a generic, stateless, protocol which can be used for
 many tasks beyond its use for hypertext, such as name servers and
 distributed object management systems, through extension of its
 request methods, error codes and headers [47]. A feature of HTTP is
 the typing and negotiation of data representation, allowing systems
 to be built independently of the data being transferred

 The Hypertext Transfer Protocol (HTTP) is an application-level
 protocol for distributed, collaborative, hypermedia information
 systems. HTTP has been in use by the World-Wide Web global
 information initiative since 1990. The first version of HTTP,
 referred to as HTTP/0.9, was a simple protocol for raw data transfer
 across the Internet.

 Practical information systems require more functionality than simple
 retrieval, including search, front-end update, and annotation. HTTP
 allows an open-ended set of methods and headers that indicate the
 purpose of a request [47].

 message
 The basic unit of HTTP communication, consisting of a structured
 sequence of octets matching the syntax defined in section 4 and
 transmitted via the connection.

 resource
 A network data object or service that can be identified by a URI,
 as defined in section 3.2. Resources may be available in multiple
 representations (e.g. multiple languages, data formats, size, and
 resolutions) or vary in other ways.

 entity
 The information transferred as the payload of a request or
 response. An entity consists of metainformation in the form of
 entity-header fields and content in the form of an entity-body, as
 described in section 7.

 representation
 An entity included with a response that is subject to content
 negotiation, as described in section 12. There may exist multiple
 representations associated with a particular response status.

 content negotiation
 The mechanism for selecting the appropriate representation when
 servicing a request, as described in section 12. The
 representation of entities in any response can be negotiated
 (including error responses).

 variant
 A resource may have one, or more than one, representation(s)
 associated with it at any given instant. Each of these
 representations is termed a `varriant`. Use of the term `variant`
 does not necessarily imply that the resource is subject to content
 negotiation.

 client
 A program that establishes connections for the purpose of sending
 requests.

 user agent
 The client which initiates a request. These are often browsers,
 editors, spiders (web-traversing robots), or other end user tools.

 server
 An application program that accepts connections in order to
 service requests by sending back responses. Any given program may
 be capable of being both a client and a server; our use of these
 terms refers only to the role being performed by the program for a
 particular connection, rather than to the program's capabilities
 in general. Likewise, any server may act as an origin server,
 proxy, gateway, or tunnel, switching behavior based on the nature
 of each request.

 origin server
 The server on which a given resource resides or is to be created.

 ache
 A program's local store of response messages and the subsystem
 that controls its message storage, retrieval, and deletion. A
 cache stores cacheable responses in order to reduce the response
 time and network bandwidth consumption on future, equivalent
 requests. Any client or server may include a cache, though a cache
 cannot be used by a server that is acting as a tunnel.

 cacheable
 A response is cacheable if a cache is allowed to store a copy of
 the response message for use in answering subsequent requests. The
 rules for determining the cacheability of HTTP responses are
 defined in section 13. Even if a resource is cacheable, there may
 be additional constraints on whether a cache can use the cached
 copy for a particular request.

 semantically transparent
 A cache behaves in a "semantically transparent" manner, with
 respect to a particular response, when its use affects neither the
 requesting client nor the origin server, except to improve
 performance. When a cache is semantically transparent, the client
 receives exactly the same response (except for hop-by-hop headers)
 that it would have received had its request been handled directly
 by the origin server.

 validator
 A protocol element (e.g., an entity tag or a Last-Modified time)
 that is used to find out whether a cache entry is an equivalent
 copy of an entity.

 upstream/downstream
 Upstream and downstream describe the flow of a message: all
 messages flow from upstream to downstream.

# Blockchain syntax

 

```
PoA-Payload  = Version *( entity-header CRLF) CRLF message-body
Version = TBD;
```

```
entity-header = entity-header  = Allow           ; Section 14.7
                      | Content-Encoding         ; Section 14.11
                      | Content-Language         ; Section 14.12
                      | Content-Length           ; Section 14.13
                      | Content-Location         ; Section 14.14
                      | Content-MD5              ; Section 14.15
                      | Content-Range            ; Section 14.16
                      | Content-Type             ; Section 14.17
                      | Expires                  ; Section 14.21
                      | Last-Modified            ; Section 14.29
                      | extension-header
entity-body =
```
