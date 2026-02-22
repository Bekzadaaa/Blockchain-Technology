# ERC-20 Token Development and Deployment

## Objective
The objective of this practical lesson is to develop, deploy, and test an ERC-20 token on the Ethereum blockchain using OpenZeppelin libraries.

## Tools Used
- MetaMask
- Remix IDE
- OpenZeppelin Contracts
- Ethereum Sepolia Test Network

## Smart Contract Description
The smart contract implements a standard ERC-20 token with custom parameters.

Token details:
- Name: MyCustomToken
- Symbol: MCT
- Decimals: 18
- Initial Supply: 1,000,000 MCT

The initial supply is minted to the contract owner during deployment.

## Smart Contract Code
The contract is based on OpenZeppelin's ERC20 and Ownable implementations.
Only the contract owner is allowed to mint new tokens.

## Deployment
- Network: Ethereum Sepolia Test Network
- Deployment method: Remix IDE with MetaMask
- The contract was successfully deployed and verified on the test network.

## Interaction with the Contract
The following functions were tested:

- `mint(address to, uint256 amount)`
  - Creates new tokens
  - Restricted to the contract owner

- `transfer(address to, uint256 amount)`
  - Transfers tokens to another address

- `balanceOf(address account)`
  - Returns the token balance of an address

All transactions were confirmed via MetaMask and are visible on Sepolia Etherscan.

## MetaMask Integration
The deployed ERC-20 token was added to MetaMask as a custom token using the contract address.
Token balances and transfers are displayed correctly in MetaMask.

## Conclusion
The ERC-20 token was successfully developed, deployed, and tested.
All required functionalities including minting, transferring, and balance tracking work correctly.