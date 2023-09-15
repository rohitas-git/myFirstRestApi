# myFirstRestApi
Rest api with NodeJs and Express (with guidance from Programming with Mosh youtube channel) <br>


# Knowledge learned about Rest-API <br>

Most common API <br>
- RESTful (RE_presentational S_tate T_ransfer) <br>

RESTful API organizes data entities or resources into a bunch of unique URIs <br>

URI - Uniform Resource Identifier <br>
URIs differentiate different types of data resources on a server <br>
URI = 'network-location'/'resource'  <br>

Client can get data about a resource by making a request to that endpoint over http  <br>

REQUEST format  <br>
'VERB' 'URI' <br>
'HEADER' <br>
'BODY' <br>

'VERB' or 'HTTP METHOD' to express intent about what to do with data <br>
POST    - CREATE <br>
GET     - READ <br>
PUT     - UPDATE <br>
DELETE  - DESTROY  <br>

'HEADER' <br>
Accept - Tells server you want data in a specific format <br>
Authorization - Used to tell server that you are allowed to make that request <br>

'BODY'  - Contains custom payload of data  <br>

RESPONSE format <br>
'httpVer' 'STATUS CODE'  <br>
'HEADERS' - contain info about server <br>
'BODY' - contains the data payload and is ususally formatted in JSON when talking about APIs <br>

'STATUS CODE' 
2** - GOOD <br>
4** - YOU MESSED UP <br>
5** - SERVER BROKEN <br>

IMPORTANT: This architecture is STATELESS

Express.js - popular framework to build rest-apis in node
