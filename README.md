# How to run

1. create balancer.js and implement the necessary code
2. run server1.js, server2.js, server3.js and balancer.js in separated command line
3. Then test the following use cases 
    * Calling http://localhost:9999/hello the first time will return “Hi I'm server 1”
    * Calling http://localhost:9999/hello the second time will return “Hi I'm server 2”
    * Calling http://localhost:9999/hello the third time will return “Hi I'm server 3”
    * Calling http://localhost:9999/hello the fourth time will return “Hi I'm server 1”

example-request.js is provided as an example one how to call a server from Nodejs

