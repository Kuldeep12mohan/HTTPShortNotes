# HTTP Crash Course

Hyper text transfer Protocol

1-Server(Client-Server communication)

URL-Locator
URI-Identifier
URN-Name

HTTP headers

metaData-- key-value sent along with request and response

--> caching,authenticatiom, manage state


-->Request headers->from client
-->response headers->from server
-->representation headers->encoding/compression
-->payload headers->data

Most common Headers

->Accept:application/json
->user-agent
->authorization-(BEARER--....)
->content-type
->cookie
->cache-control


CORS
->Access-control-allow-origin
->Access-control-allow-credentials
->Access-control-allow-method


Security
->cross-origin-embedders-policy
->cross-origin-opener-policy
->content-security-policy
->X-XSS protection


HTTP methods

GET
HEAD
OPTIONS
TRACE
DELETE
PUT
POST
PATCH
