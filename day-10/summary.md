## What I learnt 
* learnt about difference between module and functions 
* learnt about different Node js modules  and array methods like some and find 
* learnt about some keywords like NaN and their uses.
* learnt how to correctly take the arguments 
* learnt how to convert Number to Strings 



## what problems came and their solutions
* **Problem** -**Argument taking Problem** -Took the Argument like 
`$ node db.js "1", "a@mail.com","20` which was a error.
**Solution**-There are two ways to take the arguments
`node db.js 1 a@mail.com 20`
`node db.js "1" "a@mail.com" "20"`

 * **Problem**-wrote the wrong syntax `(Number "process.argv[2]" == NaN)`.
 
   **Solution**-You cannot write Number "value".
             correct way to wrire it `Number(value)` i.e-`isNaN(Number(process.argv[2])`
                      