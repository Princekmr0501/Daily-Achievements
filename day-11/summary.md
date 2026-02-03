## What I learnt 
* How the whole program works
* How to convert the  data from string to arrays 
* use of important keywords like `split`,`trim`,`slice` etc.
* How to add  and list the users using command line arguments.

## Problems and their Solutions 
**Problems**-**converting csv to javascript objects**.
* was returning js objects in a wrong way  like 
` return{id ,name,email,age};`

**Solution**- correct way ` return{id:Number(id) ,name,email,age:Number(age)};`

**Problems**-
**wrong logic of id generation** 
* I was adding the length of the total users and doing `+1` for a new ID.
`CODE`
`function newId(users){`
    `return users.length + 1;`
 ` }`
 
 **Solution**-
 * Missing the Base Case ,What if any one user is deleted
 * The length reduces by one and the new user gets the Id Of the previous user 
 * so find the last user's ID and add `+1` for a new ID.
`CODE`
`function newId(users){`
`if(users.length==0){`
`return 1 }`
    `return users[users.length-1].id + 1;`
 ` }`

**Problems**- 
* was using arrays.appendFileSync.

**Solutions**
* should use `fs.appendFileSync`.

**Problem**
* was using wrong syntax of switch case like
`case (command):`

**Solutions** 
* correct order of syntax 
`case command :`

