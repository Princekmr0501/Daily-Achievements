
## How does this whole program work 
* csv  stores the data into binary or text format 
* It sents a copy of it in the memory. 
* Now we copy this data fro memory to js as we cant work on raw data(Csv)
* Js uses RAM to access and manipulate this data 
## CONVERTING CSV DATA FROOM STRINGS TO ARRAYS 
* Addition ,deletion or any type of  modification can only be made on arrays 
* first fetch the data from csv to js file.
* use the split function to convert them into arrays 
* first put all the rows into one big aray using split("\n");
* Now make separate all the rows as different arrays using split(",);

## MAKING OF ADD FUNCTION
* Take the arguments from terminal using `process.argv`.
* Before taking the variable check if they are valid using some constraints.
* store argiments in a variable.
* Append the variable to the array list using `appendFileSync`.
* we don't need to write back to csv file unlike in deletion because we are    appending th new user to the csv file.

## MAKING OF LIST FUNCTION
* just put a for or forEach loop on users and print the users list .


