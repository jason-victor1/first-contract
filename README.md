# Deploying My First Contract

I have progressively added functionality to my Solidity contract by adding features like storing a favorite number, public list, favorite number retrieval, and update functions. I’ve built a solid contract structure. Now, it’s time to deploy this to a real testnet.

## Compilation Check

This step ensures that my contract has no errors or warnings and is fit for deployment. I go to my development environment and ensure that I have a green checkmark which indicates a successful compilation.

## Changing The Environment

The deployment process kicks off by switching from the local virtual environment (Remix VM) to MetaMask as the Injected provider. Here's how I make the switch:

1. I navigate to the deploy tab.
2. Delete any content there.
3. Change the environment.

I choose the `Injected Provider MetaMask` option. This allows the web interface to interact with my MetaMask account.

## Connecting My Account

Upon choosing MetaMask as my injected provider, I am prompted to pick a specific account for use. I choose my desired account and proceed to connect it. Next, I check my MetaMask display to ensure that my account is properly connected to Remix. It’s critical to double-check that I am on the correct testnet as this guide uses the Sepolia testnet.

If I have sufficient Sepolia ETH in my account provided from a faucet, I can now go ahead and click the "Deploy" button.

## Confirming The Transaction

Upon hitting the deploy button, MetaMask prompts me to confirm the transaction for contract deployment. Since I am on the Sepolia testnet and not on a mainnet, the money spent here is not real. I click "Confirm" to launch the contract deployment.

## Checking The Deployment

After I confirm, I should now find the following indicators that my contract deployment is successful:

- A green checkmark appears.
- Invocation status changes to ‘block confirmations’.
- The contract address appears under deployed contracts.

If I wait and refresh my Etherscan page, I’ll see a "Success" status, along with the complete details of my transaction. For deployment transactions, the input data field will be larger than normal transaction data; it contains contract creation data, along with the gas fee details because any action that alters the blockchain requires gas for implementation.

**Add Sepolia Etherscan screenshot here**

If I wait and refresh my Etherscan page, I’ll see a "Success" status, along with the complete details of my transaction. For deployment transactions, the input data field will be larger than normal transaction data; it contains contract creation data, along with the gas fee details because any action that alters the blockchain requires gas for implementation.
