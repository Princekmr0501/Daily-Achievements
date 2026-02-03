**What i Learnt**
* How to Fix the test cases 
* learnt about use of return statements use inside switch case
* Learnt how to handle cases where arguments should be defined or not defined
* Also learnt about eslint plugins 


**Problems**
* Used return function inside switch case was giving the error

**Solution**
* wrapped the whole js code in a function call
and called teh function

**Problem & Solution**
* Invalid cases of fields in update and find,soled by handling the invalid  cases outside the switch case. 
* Not using default cases inside switch failed the test cases so made default cases for each switch case
* Wrong keywords in places where some specific keywords were required like `Invalid` ,`duplicate` ,and other in invalid cases.
* `import/dynamic require` problem was still arising after using fs in import ,so the main problem was eslint plugin was not installed and imported in `.eslintric.js`