## what did i learn 
* when using tradition or terminal postgresql us e prisma client ,but when using  serverless database use prisma client +prisma Neon Adapter 
* if you modifies the schema.prisma always regenerate prisma client 

**problems and solutions**
* was not using `Adapter` correctly as using `Adapter` correctly is a necessity for neon type databases
* jwt and token was not displaying their values on the frontend so modified the code to send the error message if not returning the values(either return the full details or reutrn the error)
