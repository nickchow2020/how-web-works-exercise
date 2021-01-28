# How the Web Works Exercise
## Part One: Solidify Terminology
In your own terms, define the following terms:

### 1 What is HTTP?
HTTP stands for Hypertext Transfer Protocol,it provide a way to communicate between web browsers and 
web servers suck as making request to the web server,and display the response via the web browser

### 2 What is a URL?
URL stands for Uniform Resource Locator,like the website address,"www.google.com"

### 3 What is DNS? 
DNS stands for Domain Name System,It's convert Domain name into ID address,like a phone-book of internet

### 4 What is a query string?
query string assigns value to specific parameter to URL,we can search or update the database base on that 
value

### 5 What are two HTTP verbs and how are they different?
Most often use HTTP verbs are "get" and "post", "get" make a request to the server and response back via the browser,"post" make a request to update the database via the server

### 6 What is an HTTP request?
HTTP request means request a server from server,like make a "get" request, "post" request to update database,
or delete database with delete request

### 7 What is an HTTP response?
HTTP response is data that response back after make the request

### 8 What is an HTTP header? Give a couple examples of request and response headers you have seen.
HTTP header allow pass additional information along the HTTP request or HTTP response

HTTP header request:
Accept-Language: fr
Accept:application/json

HTTP header response:
date: Thu, 28 Jan 2021 19:56:38 GMT
content-type: application/json
server: cloudflare
cf-ray: 618d4723dd11d34a-LAX
content-encoding: br


### 9 What are the processes that happen when you type “http://somesite.com/some/page.html” into a browser?
1. turn "somesite.com" into some IP address 
2. connect to that IP address 
3. select port 80 
4. use HTTP protocol 
5. request some/page.html 
6. response some/page.html







