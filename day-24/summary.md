## What did i learn 
* learnt how to write the code for commnicating with the `llm`
* learnt some important information about `.env` files,  difference between `ES modules` vs `clean JS version`,how to check file structures using git commands ,about `UTF-8`,about `choices[0]`.

## Problems and their solutions 
* I was using `require ` and `import` function  in the same file ,which was giving errors, 
 so either use `require ` or import not both.
* Was loading `.env` file inside the main project but it should be inside the backend folder (inside `.gitignore `)
* was using  fetch and import together but one should be used either fetch or either import ,if you are using fetch you have to get the llm link manually otherwise using import can automatically fetch the link.

