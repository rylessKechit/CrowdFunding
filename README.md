# Crowdfunding App

## Overview

This app allows users to create and fund projects using smart contracts built on the Ethereum blockchain. The smart contracts are developed using Solidity and are deployed on the Ethereum network using Hardhat. The frontend of the app is built using React, Vite, and Tailwind CSS, and is deployed using Netlify.

## Getting Started

- Clone the repository: git clone https://github.com/rylessKechit/CrowdFunding.git
- Install dependencies -> `npm install`
- Start the development server -> `npm run dev`
- Connect to the Ethereum network using Hardhat -> `npx hardhat node`
- Deploy the smart contracts -> `npx hardhat run scripts/deploy.js`
- Build and deploy the frontend to Netlify -> `npm run build && netlify deploy`
- Interact with the contracts using the app's UI

## Features
- Create a project with a funding goal and deadline
- Contribute to a project using Ether
- View a project's funding progress and contributors
- Withdraw funds from a successful project (in development)

## Technical Details

- Smart contracts are developed using Solidity and are deployed on the Ethereum network using Hardhat.
- The frontend of the app is built using React, Vite, and Tailwind CSS, and is deployed using Netlify.
- The app uses Web3.js to interact with the smart contracts on the Ethereum network.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.