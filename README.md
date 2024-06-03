# Create-and-Mint-Token

This is a basic token contract implemented in Solidity. It allows for token minting, burning, and transfer functionality. The contract owner has the authority to mint new tokens, while any address can burn their own tokens and transfer tokens to other addresses.

# Contract Details

Contract name: MyToken1

License: MIT

Solidity version: 0.8.25

# Contract Variables

owner: The address of the contract owner.

tokenName: The name of the token.

tokenSymbol: The symbol or abbreviation of the token.

totalSupply: The total supply of the token.

balances: A mapping that stores the token balances of addresses.

# Functions

# constructor()
Initializes the contract owner, token name, token symbol, and total supply.
The contract owner is set as the deployer of the contract.
mint(address _address, uint256 _value)

# Mints new tokens and assigns them to the specified address.
Only the contract owner can call this function.
Increases the total supply of the token.

# burn(address _address, uint256 _value)
Burns (destroys) tokens from the specified address.
The address must have a sufficient balance to burn.
Decreases the total supply of the token.

# transfer(address _from, address _to, uint256 _value)
Transfers tokens from one address to another.
The sender must have a sufficient balance to transfer.
Decreases the sender's balance and increases the recipient's balance.

# Getting Started
# Executing program
To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the code from the holocoin.sol file.

To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to a compatible version, and then click on the Compile button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the mint function to add specific number of tokens to the supply, burn function to burn a specific number of tokens, or transfer function to send tokens to another address. Once you filled the address and value in your chosen function, click on the "transact" button to execute the function and you'll see a message from the console.
