# XENEAFUND Web3 Crowd-Funding Platform 

## Introduction



XENEA Platform is a decentralized application (DApp) that allows users to create and fund projects using blockchain technology. By leveraging the power of smart contracts and decentralized finance (DeFi), this platform ensures transparency, security, and immutability in crowdfunding campaigns.

## Features

- **Decentralized**: Operates on a blockchain, removing the need for intermediaries.
- **Smart Contracts**: Automates the process of funding and ensures funds are only released when predefined conditions are met.
- **Transparency**: All transactions and campaign details are publicly available on the blockchain.
- **Security**: Funds are securely stored in smart contracts and only accessible under specific conditions.
- **Immutable Records**: Once recorded, transactions cannot be altered, ensuring the integrity of the data.

## Technology Stack

- **Frontend**: React.js, Web3.js
- **Blockchain**: XENEA, Solidity
- **Database**: IPFS (InterPlanetary File System) for decentralized storage
- **Smart Contracts**: Solidity


## Usage

### Creating a Campaign

1. Connect your wallet (e.g., MetaMask) to the platform.
2. Navigate to the "Create Campaign" page.
3. Fill in the details of your campaign (title, description, goal amount, deadline).
4. Submit the form to create your campaign. A transaction will be sent to the blockchain to record the campaign details.

### Funding a Campaign

1. Browse through the list of active campaigns.
2. Select a campaign to view its details.
3. Enter the amount you wish to contribute and submit the form.
4. Confirm the transaction in your wallet. The funds will be transferred to the campaign's smart contract.

### Withdrawing Funds

1. Once the campaign reaches its goal and the deadline has passed, the campaign creator can withdraw the funds.
2. Navigate to the "My Campaigns" page and select the campaign.
3. Click the "Withdraw Funds" button and confirm the transaction in your wallet. The funds will be transferred to the creator's address.

## Smart Contracts

The platform uses a set of smart contracts to manage campaigns and contributions.

### CampaignFactory.sol

This contract is responsible for creating and managing individual campaigns.

### Campaign.sol

This contract represents a single campaign. It handles contributions, goal tracking, and fund withdrawal.


