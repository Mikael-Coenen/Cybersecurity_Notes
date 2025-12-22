## HTTP/HTTPS
- HTTP, or hyper-text transfer protocol is the set of rules when trasmitting data about a webpage, such as HTML and images, from a web server to a web client
- HTTPS, or hyper-text transfer protocol secure is the same as HTTP but now it uses encryption to make sure people cant see data you are recieving or sending

## URL
- Uniform Resource Locator, or URL, is made up of different componenets:
    - Scheme: the protocol for the URL such as HTTP, HTTPS, etc
    - User/password: Sometimes a URL will have a username and password that locks the site
    - Host: Domain name or IP address of the web server your trying to access
    - Port: Port your trying to connect to, usually 80 for HTTP and 443 for HTTPS but can be any port from 1-65535
    - Path: File name of the resource your trying to access
    - Query: Additional information about the resource your trying to access
    - Fragment: Link to specific point on a page (eg. if the page is quite long)
 
## HTTP Request & Response
- This request will contain the protocol, protocol version, what website we are trying to access, the host of that website, what browser we are using, and what refered us to that site
- A response comes back with confirmation if the request was approved or denied, then it contains info on the server, date, content type of the requested info, how long that requested info is, and then the requested info itself

## HTTP Methods
- HTTP methods are a way for clients to show their intended action when making a HTTP request. The most common examples are:
    - GET: getting info from a web server
    - POST: Submitting data to a web server and potentially creating new records
    - PUT: Submitting data to a web server to update it
    - DELETE: Deleting any info from a web server
## HTTP Status Codes
- HTTP status codes inform a client on the outcome of their HTTPS request
- Ranges for these status codes and what they mean:
    - 100-199: Part of their request was accepted so they should send the rest of their request
    - 200-299: Their request was a success
    - 300-399: Their request is getting redirected elsewhere
    - 400-499: There was an error with their request
    - 500-599: There is a major problem with the server
## Headers
- Headers are additional bits of data you send to the web server when making a request
- Some headers include: host (which website from a server you want), your browser info (so the web server can properly load HTML, CSS, etc for your browser), content-length (to ensure server isnt missing any data), content-type (what type of
content is being returned), and compression capabilities (what method has been used to compress the data to send)

## Cookies
- Cookies are small bits of data that are saved about a user on your device which sends that data to a web server
- They remind a web server who you are as they save info about you such as your name
