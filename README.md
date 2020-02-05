# APIs

## Students Will Be Able To:
 - [] Describe the client-server model and request-response cycle
 - [] Identify examples of clients and servers, both on their local computers and remotely connected
 - [] Identify examples of requests and responses
 - [] Understand the difference between a request that returns HTML and an API request that returns JSON
 - [] Understand the basic pieces of making HTML and JSON requests
    - For simple requests, you only need 2 things: HTTP verb and URL
    - HTTP verb: this will almost always be `GET`, kind of like how a data scientist's SQL query will almost always be `SELECT`.  But there are other verbs, including `POST` and `PATCH`, which are like `INSERT INTO` and `UPDATE`
    - URL: this is the string representing the location of the resource.  It can also be called a "path", or an "endpoint"
 - [] Use a browser to make HTML and JSON requests
    - This just means typing the URL into the browser.  It will always be a `GET` request.
    - The browser will show HTML or JSON depending on the URL.  So, `reddit.com` shows you HTML, whereas `reddit.com/.json` shows you JSON.
 - [] Use Postman to make HTML and JSON requests
    - Postman has input fields where you can type the URL and select the HTTP verb from a drop-down
    - Remember that this is a good tool for exploration/figuring out how to use an API (better than Chrome), but it's not the final product
 - [] Practice reading someone else's Python code that uses the `requests` library
 - [] Use Python `requests` library to make JSON requests
 - [] Practice reading the documentation for an API
