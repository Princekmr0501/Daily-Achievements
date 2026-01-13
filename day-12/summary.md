## USE of Eslint 
* what is Eslint and the use of it .
* went through  and learnt about different types of errors and warning while installing Eslint.
* learnt about the differnce between `rm --cached filename` and `.gitignore`.
* learnt about  `break` can also be used inside `if`,if it's inside a `case`;
*  `return` should always be inside a function
* learnt to use rules according to the user's convienience.

## Problems and their Solutions 
**Problem =>** **return statement without a function** 
*  **wrong code** 
 if(!name || !email || isNaN(age)||age<0){
        console.log("enter a valid argument")
        return 
    }

**Solution**- correct way 

if(!name || !email || isNaN(age)||age<0){
        console.log("enter a vlid argument")
        
        break
    }
    
    or wrap it inside a function like 
   
   `function addUser(user){`

       `if(!name || !email || isNaN(age)||age<0){`

    `console.log("enter a valid argument")`
    `break`
    `}`
    `}`

**Problems** 
**.gitignore vs rm --cached filename (For Untracking the sensitive files)**
* Due to earlier commit git ws tracking users.csv which contains the important information
**Solutions**
* Made the users.csv untrackable by running the code 
* `rm --cached filename`(This is used to untrack the files which are being tracked due to   earlier commit).
* Now put that file into the `.gitignore`.(`.gitignore` confirms that the in the future anyone's users.csv file doesn't get tracked );

**Problems** 
**Node version and eslint version was not working together,due to which `.eslint.config.mjs` file was not made**

**Solutions**
* There are two soutions either update and reinstall the Node LTS or make the `.eslint.config.mjs` file manually
* I made it manually

**Problems**-**Differet  problems while installing Eslint**.
* Teminal output while installing 
npm error canceled
npm error A complete log of this run can be found in: C:\Users\PARMENDRA KUMAR\AppData\Local\npm-cache\_logs\2026-01-12T10_03_07_332Z-debug-0.log
 
 **Solution**-
 *  Thia means- npm detected that:
 * package-lock.json is out of sync,
 * npm cache is partially corrupted, OR
* An install was interrupted (cancelled earlier — which did happen)
 TO fix this I deleted package.lock.json and and reinstalled npm 
 `CODE`
 `npm cache clean --force`
  `npm install`
  `npx eslint --init`


**Problem**
**List of warnings containing keywords like LRF AND CLRF and a list of warning was shown**

**Solutions** 
* was due to node modules files creating the errors 
* sent the node modules to the .gitignore.
* Type `node_modules/` inside .gitignore.
