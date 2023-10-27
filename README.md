# Block My Event

Block My Event is a decentralized ticketing platform built with ReactJS, Hardhat, and Solidity. Users can buy tickets for various events using Ethereum (ETH) and enjoy a secure and transparent ticketing experience.


## Features

- Event Listings: View a list of upcoming events and their details, including event name, date, venue, and available tickets.
- Ticket Purchase: Buy tickets for desired events using Ethereum (ETH) as the payment method.
- Smart Contract Integration: Utilize Solidity smart contracts to handle the ticket purchasing process securely and transparently.
- Metamask Integration: Connect with your Metamask wallet to make seamless ETH transactions.

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/). Recommended to use the LTS version.
- Install [MetaMask](https://metamask.io/) on your browser.


## Installation

1. Clone the repository: `git clone https://github.com/Mudit-Jxin7/TicketMaster-web3.git`
2. Navigate to the project directory: `cd TicketMaster-web3`
3. Install the dependencies: `npm install`
4. Run tests: `npx hardhat test`
5. Start Hardhat node: `npx hardhat node`
6. Run deployment script In a separate terminal execute: `npx hardhat run ./scripts/deploy.js --network localhost`
7. Start frontend: `npm run start`

## Dependencies

The project utilizes the following dependencies:

- React: JavaScript library for building user interfaces.
- Hardhat: Development environment for Ethereum projects, including Solidity smart contract compilation and deployment.
- Solidity: High-level programming language for writing smart contracts.
- Metamask: Browser extension for connecting to Ethereum networks and managing wallets.

For a complete list of dependencies and their versions, please refer to the `package.json` file.

## Smart Contracts

The TicketMaster project uses Solidity smart contracts to handle ticket purchasing and verification. The contracts can be found in the `contracts/` directory.

To deploy the contracts, you need to set up a local development network using Hardhat. Update the `hardhat.config.js` file with your preferred network configurations.


## Acknowledgments

- Hardhat: Special thanks to the Hardhat team for providing an excellent development environment for Ethereum projects.
- ReactJS: Thanks to the ReactJS community for their robust and user-friendly library.
- Solidity: Special thanks to the Solidity community for their powerful smart contract language.


