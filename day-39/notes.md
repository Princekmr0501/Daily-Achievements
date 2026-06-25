## learnt about auth and authorization middleware ,
* When a project request for creating a project is sent then it first passes through the auth middleware which extracts the role and user id of the token and paases it on  to the authorization middleware 
* Authorization middlewate checks that the role is allowed to create the project or not . if yes it is sent forward otherwise it sends a an error message 
