# http-status-codes


An HTTP status code is a server response to a browser’s request. When you visit a website, your browser sends a request to the site’s server, and the server then responds to the browser’s request with a three-digit code: the HTTP status code.

## Common HTTP status code classes:

__1xxs__ – Informational responses: The server is thinking through the request. A 1xx Informational status code means that the server has received the request and is continuing the process. A 1xx status code is purely temporary and is given while the request processing continues. For most tasks you won't encounter these much, as it's not the final response to the request.

__2xxs__ – Success! The request was successfully completed and the server gave the browser the expected response. A 2xx Succesful status code means that the request was successful and the browser has received the expected information. This is generally the one you want to see, as it means that the request was a success and has been received, understood and accepted it.

__3xxs__ – Redirection: You got redirected somewhere else. The request was received, but there’s a redirect of some kind. A 3xx Redirection status code means that you have been redirected and the completion of the request requires further action. Redirects are a natural part of the internet and you shouldn't be scared to have 3xx redirect status codes on your website.

__4xxs__ – Client errors: Page not found. The site or page couldn’t be reached. (The request was made, but the page isn’t valid — this is an error on the website’s side of the conversation and often appears when a page doesn’t exist on the site.)

__5xxs__ – Server errors: Failure. A valid request was made by the client but the server failed to complete the request. A 5xx Server error status code means that while the request appears to be valid, the server could not complete the request. If you're experiencing 5xx server errors for your website, you should immediately look at your server. 

#Status code	Meaning : 

## 1xx Informational	 
**100**	Continue
**101**	Switching protocols
**102**	Processing
**103**	Early Hints
 	 
## 2xx Succesful	 
**200**	OK
**201**	Created
**202**	Accepted
**203** Non-Authoritative Information
**204**	No Content
**205**	Reset Content
**206**	Partial Content
**207**	Multi-Status
**208**	Already Reported
**226**	IM Used
 	 
## 3xx Redirection	 
**300**	Multiple Choices
**301**	Moved Permanently
**302**	Found (Previously "Moved Temporarily")
**303**	See Other
**304**	Not Modified
**305**	Use Proxy
**306**	Switch Proxy
**307**	Temporary Redirect
**308**	Permanent Redirect
 	 
## 4xx Client Error	 
**400**	Bad Request
**401**	Unauthorized
**402**	Payment Required
**403**	Forbidden
**404**	Not Found
**405**	Method Not Allowed
**406**	Not Acceptable
**407**	Proxy Authentication Required
**408**	Request Timeout
**409**	Conflict
**410**	Gone


 	 
## 5xx Server Error	 
**500**	Internal Server Error
**501**	Not Implemented
**502**	Bad Gateway
**503**	Service Unavailable
**504**	Gateway Timeout
**505**	HTTP Version Not Supported
**506**	Variant Also Negotiates
**507**	Insufficient Storage
**508**	Loop Detected
**510**	Not Extended
**511**	Network Authentication Required

## Referrence: 
#### https://moz.com/learn/seo/http-status-codes
#### https://www.restapitutorial.com/httpstatuscodes.html
#### https://umbraco.com/knowledge-base/http-status-codes/
#### https://restfulapi.net/http-status-codes/
