# HTTP/HTTPS

## Methods

- GET 
	- To retrive specific data
- PUT 
	- At a specific resource replce the given data
- POST
	- Add new data or send some data to server to process
- DELETE
	 - Deletes the specified resource
- HEAD
	- Similar to get but without response body
- PATCH
	- To update small part of data
- TRACE
- OPTIONS
- CONNECT

## Status codes

- 100-199 - Informational
	- 100 - Continue
	- 101 - Upgrading protocol
- 200-299 - Success
	- 200 - OK
	- 201 - Created
	- 202 - Accepted
- 300-399 - Redirects
	 - 300 - Can have multiple response
	 - 301 - Moved permanently
	 - 302 - Found URI - Changed temporarily
	 - 307 - Temporary Redirect
	 - 308 - Permanent Redirect
- 400-499 - Client Error
	 - 400 - Bad Request
	 - 403 - Forbidden
	 - 404 - Not Found
	 - 405 - Method not allowed
	 - 408 - Request Timeout
- 500-599 - Server Error
	 - 500 - Internal server errors
	 - 501 - Invalid method
	 - 502 - Bad Gateway
	 - 503 - Service unavaiable

## Headers
### RequestHeader
- Request type
- User agent - information of system
- Accept - type of response it will accept
- Accept-Language - Language of data
- Accept-Encoding - What type of compression
- Referer - From which URI the request came from
- Connection - need to keep open and wait till response comes or close

__REF : [Click](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers) __
