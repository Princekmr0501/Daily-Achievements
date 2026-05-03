## What did i learn
* learnt about properly syncing the database with your local computer .
* use `npx prisma generate` if you are interacting with the client issue like generator and db in schema.prisma 
* if you are modifying the database structure like model user inside the schema.prisma then run `npx prisma migrate dev `as it updates the databse according to the schema.prisma using migration files
* learnt how to make migration files ( files that contain the information of updating the database according to the schema.prisma ) but not apply it just making it for review

**Problems and solution**
* BASE_URL should be inside the `.env` file so that you can take control of all the requests you are making from one place.
* Manually adding a table in the database was  creating a problem so delted the manually added table and ran migrate command.