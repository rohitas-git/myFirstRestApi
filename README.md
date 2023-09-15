# myFirstRestApi
Rest api with NodeJs and Express (with guidance from Programming with Mosh youtube channel)


# Knowledge learned about Rest-API

Most common API
- RESTful (RE_presentational S_tate T_ransfer)

RESTful API organizes data entities or resources into a bunch of unique URIs

URI - Uniform Resource Identifier
URIs differentiate different types of data resources on a server
URI = <network-location>/<resource>

Client can get data about a resource by making a request to that endpoint over http

REQUEST format
<VERB> <URI>
<HEADER>
<BODY>

<VERB> or <HTTP METHOD> to express intent about what to do with data
POST    - CREATE
GET     - READ
PUT     - UPDATE
DELETE  - DESTROY 

<HEADER>
Accept - Tells server you want data in a specific format
Authorization - Used to tell server that you are allowed to make that request

<BODY>  - Contains custom payload of data 

RESPONSE format
<httpVer> <STATUS CODE>
<HEADERS> - contain info about server
<BODY> - contains the data payload and is ususally formatted in JSON when talking about APIs

<STATUS CODE>
2** - GOOD
4** - YOU MESSED UP
5** - SERVER BROKEN

IMPORTANT: This architecture is STATELESS

Express.js - popular framework to build rest-apis in node
