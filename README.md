# Credit Card Validator

This project is a challenge in the Front End Career Path course on Codecademy. The goal is to optimize the verification process of credit cards by checking if they are valid using functions and loops.

## Project Context

The company suspects that credit card distributors have been mailing out cards with invalid numbers. In this project, you play the role of a clerk responsible for checking the validity of credit cards. Your task is to use your knowledge of functions and loops to handle multiple credit cards at a time, optimizing the verification process.

## Credit Card Arrays

```javascript
// All valid credit card numbers
const valid1 = [4, 5, 3, 9, 6, 7, 7, 9, 0, 8, 0, 1, 6, 8, 0, 8];
// ... (other valid credit card arrays)
// All invalid credit card numbers
const invalid1 = [4, 5, 3, 2, 7, 7, 8, 7, 7, 1, 0, 9, 1, 7, 9, 5];
// ... (other invalid credit card arrays)
// Can be either valid or invalid
const mystery1 = [3, 4, 4, 8, 0, 1, 9, 6, 8, 3, 0, 5, 4, 1, 4];
// ... (other mystery credit card arrays)
// An array of all the arrays above
const batch = [...];
```



### Functions

```javascript
validateCred(arr)
```
This function checks the validity of a credit card number.

```javascript
findInvalidCards(arr)
```
This function returns an array of invalid credit card numbers from a given batch.

```javascript
idInvalidCardCompanies(arr)
```
This function identifies and returns an array of companies with invalid credit cards.



### How to Use

    1. Clone the repository.
    2. Open the project in your preferred code editor.
    3. Modify the credit card arrays or add new ones as needed.
    4. Run the functions to check for valid/invalid cards or identify invalid card companies.

Feel free to explore and customize the project as you see fit. Happy coding!

