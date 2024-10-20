# CountFI

CountFI is a GameFI project that allows users to mint a unique NFT based on certain mathematical properties. The game revolves around specific actions that modify a value, and once the required value is reached, a unique NFT is minted for the user.

## Features
- Mint NFTs: Users can mint unique NFTs based on game interactions.
- Mathematical Actions: The game includes three types of actions:
  - Increment: Increases the value by 1.
  - Decrement: Decreases the value by 1.
  - Random: Randomly chooses to either increment or decrement the value.

When the target value is reached, a single unique NFT will be minted and added to the user's collection.

## Technologies
- Move Language: Used for smart contract development.
- Aptos Blockchain: Used to deploy and interact with the smart contracts.

## How It Works
1. Users perform actions (increment, decrement, or random).
2. Once the desired value is reached through these actions, a unique NFT is minted.
3. This NFT represents the outcome of the user's interaction within the game.

## Getting Started
To get started with CountFI, ensure you have the following installed:
- Aptos CLI
- Move Language SDK

You can deploy the smart contracts on the Aptos blockchain and interact with them using the appropriate commands.

##Deploy the Smart Contract
To deploy the smart contract:

Install Aptos CLI.

Update the Move.toml file with your wallet address:

-aptos init
-Add your Account addr here for Deployment
-aptos_count = "0x5ed4664ecfac74f55a37fb7d1122eee8925d93216076cdf0ca9a0e53f495a0eb"
-Compile and publish the contract:

-aptos move compile
-aptos move publish

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
