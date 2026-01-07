## What I learnt 
* Learnt about Node js 
* Why do we use Node js 
* Why Node js is better than browsers 
* Why Engines Node js uses and who make these engines 

## what problems came and their solutions
* **Problem** - **LICENSE PROBLEM** -While installing the Node js, a security problem arose in which windows was not letting the tools of Node js to install on my local machine.
* **Solution**- *Open powershell
                * Type the code -Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned
                * give the permission to execute.
                * problem solved 
* **Problem** - **Not fetching data from servers** -While accessing the data from the server    through https requests ,the server was showing **undefined**
* **Solution**- *check the format of the data which you are accessing and want to be shown on the server ,both data formats should be same.
                * Also check that the varibale tmust be declared before the code executes or runs  (In my case I declared the variable  before the path.)
                * problem solved                 