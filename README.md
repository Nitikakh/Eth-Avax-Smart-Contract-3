Module 3 - Mtoken

An ERC20 token contract called Mtoken has been implemented on the Ethereum network. Basic token functions including minting, transferring, and burning tokens are included in this contract. It provides a straightforward illustration of how to utilize and implement the ERC20 standard for custom tokens.


Prerequisites :

1. Solidity ^0.8.13

2. Node.js and npm

3. Truffle or Hardhat

4. MetaMask or any Ethereum wallet


Getting Started

Steps:

1. Clone/Download the Code:

Obtain the smart contract code (Mtoken.sol) from a repository or download it directly.

Install Dependencies:

2. Open a terminal in the project directory and run:

  Bash
  npm install

This installs the necessary libraries for development and testing.

3. Configure Deployment Framework:

Follow the chosen framework's documentation to set up the configuration.
This typically involves creating configuration files and specifying the location of the smart contract code.
Tutorials and documentation for Truffle and Hardhat can be found on their respective websites.

4. Deploy the Contract:

Use your chosen framework's commands to deploy the contract to a blockchain network.

You'll have options to deploy to different environments:

Local Development Network: Ideal for initial testing in a simulated environment.

Testnet: Public test network for blockchain platforms (e.g., Rinkeby for Ethereum). Use testnet tokens (often obtained from faucets) for this stage.

Mainnet: Public blockchain network (e.g., Ethereum Mainnet). This involves real cryptocurrency and requires careful consideration before deploying.

5. Interact with the Contract (Using Your Wallet):

Connect your Ethereum wallet (e.g., MetaMask) to the chosen blockchain network (local/testnet/mainnet).

Interact with Contract Functions: Your wallet interface should allow interaction with the deployed contract:

Minting: This function is restricted by the onlyOwner modifier. If you deployed the contract, you can call this function to mint the initial token supply (100 tokens) to your address.

Transferring: Use the token_transfer function to specify the recipient address and the amount of tokens to transfer.
Burning: Use the token_burn function to indicate the address from which tokens are being burned and the amount to be removed from circulation.


Usage:-

Once the contract is deployed, you can interact with it using a web3-compatible wallet or through scripts.

Minting Tokens: 

Tokens are minted to the 'deployer's address' upon contract deployment.

Transferring Tokens: 

To transfer tokens, call the 'token_transfer' function with the recipient's address and the amount of tokens.


Burning Tokens

To burn tokens, call the 'token_burn' function with the address and the amount of tokens.



Auther: 

Nitika Khatana @nitikakhatana656


Licence:

This MyToken is licensed under the MIT License














