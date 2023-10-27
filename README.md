# Block My Event

In response to the pervasive issue of unfair and insecure event ticketing, which has seen concert tickets fall into the hands of scalping bots and sold at exorbitant prices on the black market, we want to transform the ticketing industry to a more secure haven. Our primary motivation is to create a system that champions the interests of genuine fans. To tackle this problem, we've harnessed the potential of blockchain and Ethereum technology to establish Block my Event, groundbreaking ticketing platform which operates by issuing tickets, ensuring their authenticity and effectively thwarting scalpers from exploiting fans. Our ultimate goal is to eliminate ticket scarcity and the associated scalping woes, ushering in a new era where events become accessible, enjoyable, and secure for everyone.

## Features
<img width="725" alt="Screenshot 2023-10-27 at 12 35 56 PM" src="https://github.com/Ukd1796/blockmyevent/assets/71224019/dc457e34-9b31-445d-9962-b709669a7c18">

## Requirements For Initial Setup
- Install [NodeJS](https://nodejs.org/en/). Recommended to use the LTS version.
- Install [MetaMask](https://metamask.io/) on your browser.

## Installation

1. Clone the repository
2. Navigate to the project directory
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

Block my event uses Solidity smart contracts to handle ticket purchasing and verification. The contracts can be found in the `contracts/` directory. To deploy the contracts, you need to set up a local development network using Hardhat. Update the `hardhat.config.js` file with your preferred network configurations.

## Technology Stack

<img width="754" alt="Screenshot 2023-10-27 at 12 37 41 PM" src="https://github.com/Ukd1796/blockmyevent/assets/71224019/e5cd01b7-1912-4efb-ae10-61f4571e8209">

## Demonstration
<img width="984" alt="Screenshot 2023-10-27 at 12 38 54 PM" src="https://github.com/Ukd1796/blockmyevent/assets/71224019/806c9d3b-acbb-44be-b41f-6556379a54dd">
<img width="992" alt="Screenshot 2023-10-27 at 12 39 16 PM" src="https://github.com/Ukd1796/blockmyevent/assets/71224019/67cf65c5-7d6c-4e8d-8144-810e21dafa22">
<img width="1020" alt="Screenshot 2023-10-27 at 12 39 37 PM" src="https://github.com/Ukd1796/blockmyevent/assets/71224019/f24891bf-55c7-425b-bdd5-86a684fecfd3">
<img width="974" alt="Screenshot 2023-10-27 at 12 39 53 PM" src="https://github.com/Ukd1796/blockmyevent/assets/71224019/6ee0c797-3dab-4529-a7f7-bc832ea6a7b9">
<img width="354" alt="Screenshot 2023-10-27 at 12 40 11 PM" src="https://github.com/Ukd1796/blockmyevent/assets/71224019/eddf8ed5-7927-4be7-abe1-edfa6d8f79ee">




