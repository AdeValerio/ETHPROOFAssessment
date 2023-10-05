# ETHPROOFAssessment
# Token Contract 
The Token Contract demonstrates the basic syntax, functionality and understanding of the developer with Solidity programming language. This program is a project for ETH: Proof Assessment.

## Description

The Token Contract is a basic Ethereum token contract designed to provide token creation (minting) and destruction (burning) functionality. Store information about the token, including its name, abbreviation, and total supply. Maintain a mapping of addresses to token balances. Provide a mint function to increase the total supply and the balance of a specified address. Offer a burn function to decrease the total supply and the balance of a specified address

## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.
After accessing the Remix website, create a new file. Save this newly created file with a .sol extension, such as "TokenContract.sol." Then, proceed to copy and paste the provided code into the file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.18" (or another compatible version), and then click on the "Compile HelloWorld.sol" button.
Tip: You can use CTRL + S to compile your code or just toggle the Auto compile in the "Solidity Compiler" tab

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "TokenContract" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by providing an address and a positive value for both the Mint or Burn functions. Mint Function will mint (add) tokens to the address you have provided.
The Burn Function on the other hand will burn (remove) tokens from the address you have provided. Do take note that the function doesn't allow you to burn tokens more than you have. 
To check the Balance, you must provide the address you have used for the mint and burn functions. 
You can check the Token Name and Token Abbreviation by clicking the TokenN and TokenA button.
You can check the Token Total Supply by clicking the TokenS button.

## Authors

Andre Martee Valerio
[@Dr_EanValerio](https://twitter.com/Dr_EanValerio)

## License

This project is licensed under the MIT License - see the LICENSE.md file for details
