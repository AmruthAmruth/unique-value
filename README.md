# unique-value

A simple utility to check if a value exists in an array. Useful for validating if an email or any other value already exists in a list.

## Installation

You can install this package using npm:

npm i check-value-in-array


Usage
Importing the Package
You can import the function in your project like this:

const valueExistsInArray = require('check-value-in-array');

Checking if a Value Exists in an Array
Here's how you can use the function:

const uniquevalue = require('check-value-in-array');

const emails = ['test@example.com', 'user@example.com', 'admin@example.com'];
const emailToCheck = 'user@example.com';

 const result= valueExistsInArray(emails, emailToCheck)
 console.log(result)


 API
valueExistsInArray(arr, value)

arr (Array): The array to check.
value (*): The value to check for.
Returns: boolean - Returns true if the value exists in the array, false otherwise.


Contributing
Contributions are welcome! Please open an issue or submit a pull request.