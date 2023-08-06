# Smart Contract - ETH + AVAX: Functions and Errors

## Overview
This solidity program demonstrates the usage of three important error handling functions: `require()`, `revert()`, and `assert()` within a smart contract. The contract aims to handle age verification for a user before processing a transaction. Additionally, it includes handling the divide by zero error.

## Description
The contract contains three main functions to handle various error scenarios. First, the `RequireCheck()` function verifies the user's age and performs the requested transaction to their account if they are 18 years or older. Second, the `RevertCheck()` function accomplishes the same task using the `revert()` function to handle errors when the user's age is less than 18. Finally, the `AssertCheck()` function ensures that a division by zero error is avoided by using the `assert()` function.

## Getting Started

### Running the Program
To execute this program, you can use Remix, an online Solidity IDE. To get started, access the Remix website at https://remix.ethereum.org/.

Once you're on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., contract.sol). Then, copy and paste the provided code into the file.

To compile the code, navigate to the "Solidity Compiler" tab in the left-hand sidebar. Ensure the "Compiler" option is set to "0.8.4" (or a compatible version), and then click on the "Compile contract.sol" button.

After successful compilation, deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the contract from the dropdown menu, and then click on the "Deploy" button.

Now, you can provide your age, the amount of tokens you want, and two integers for the division operation. Proceed to call each function `RequireCheck()`, `RevertCheck()`, and `AssertCheck()` with the required inputs and press transact.

## Author
Sutirtho Chakravorty
Email: sutirthochakravorty@gmail.com

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
