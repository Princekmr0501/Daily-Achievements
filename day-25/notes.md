## Structured the project and fixed somelnes which were breaking the code 

* called out the askllm function from other file through
 `const askllm = require("./connectors/llm")`.
 
* `uptime` tells about from what time a server is running 
* `environment` tells about who is using the server ,if it's a user it will print 
`production` otherwise `development` for  developers.
