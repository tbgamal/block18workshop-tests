# Block 18 - Workshop I

## Unit-Tests - A function called "multiplication"


### Pseudocode
1. Input of two numbers (a,b) and multiplies it;
2. returns a value of number

### Tests

😃 correctly returns number a multiplied by number b   
😃 can correctly return decimal number  
😃 can correctly return negative number  
😃 returns only one value of number   
😡 returns error if string is inputted  
😡 cannot return a fraction  
😡 cannot input more than 2 numbers

## Unit-Tests - A function called "concatOdds"

### Pseudocode
1. Input two arrays of integers with as arguments
2. Example: concatOdds([3, 2, 1], [9, 1, 1, 1, 4, 15, -1]) should result in [-1, 1, 3, 9, 15]
3. Inputs considered to unexpected should not affect the returned value

### Tests

😃 correctly returns an array of odd numbers only   
😃 can identify and correctly return both negative and absolute number in the right order
😡 should not return any even numbers  
😡 should not return any strings  
😡 cannot input more than 2 arrays

## Functional-Tests - Shopping cart checkout feature

### Pseudocode
1. Allows user  to check out as both guest (without account) and logged-in user
2. Should ask non-member to create an account after checking out
3. Should ask for payment method
4. Should ask for basic contact and address info

### Tests

😃 user with or without account should be able to check-out their cart items   
😃 membership sign-up should pop-out after Guest checks-out   
😡 cannot proceed without providing payment methods  
😡 cannot proceed without providing contact info and address  
