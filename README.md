CREATE A TOKEN

The project "Create a token" focuses on creating a token and using it to "mint" user defined value into it, or to "burn"(withdraw) user defined value from it. 

DESCRIPTION

This program creates a token and performs two functions on it, that are: "mint" and "burn". For the "mint" function, the user defined value is deposited into the token, whereas, for the "burn" function, the user defined value is withdrew from the token.

1. Your contract will have public variables that store the details about your coin (Token Name, Token Abbrv., Total Supply)
2. Your contract will have a mapping of addresses to balances (address => uint)
3. You will have a mint function that takes two parameters: an address and a value. The function then increases the total supply by that number and increases the balance of the address by that amount.
4. Your contract will have a burn function, which works the opposite of the mint function, as it will destroy tokens. It will take an address and value just like the mint functions. It will then deduct the value from the total supply and from the balance of the address.
5. Lastly, your burn function should have conditionals to make sure the balance of account is greater than or equal to the amount that is supposed to be burned.

GETTING STARTED

Software requirement - Remix IDE

Executing program -

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/. Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., myToken.sol). 

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.4" (or another compatible version), and then click on the "Compile myToken.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "myToken" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling mint and burn functions. Click on the "myToken" contract in the left-hand sidebar, and then click on the "mint" function. Enter the address into the address bar and specify some value.  Finally, click on the "transact" button to execute the function and the value will be deposited into the token. Click on the "burn" function. Enter the address into the address bar and specify some value.  Finally, click on the "transact" button to execute the function and the value will be withdrawn from the token.

AUTHORS

Khushi Gupta
Khushi-1703
