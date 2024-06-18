# DeFi-Empire

## Introduction

The "DeFi-Empire" project introduces an ERC20 token named "key" (KY) and a Vault contract. KY follows the ERC20 standard for decentralized transactions, incorporating features such as total supply tracking, balance management, and event logging for transfers and approvals. The Vault contract interacts with KY through the IERC20 interface, offering users a secure platform to deposit and withdraw funds. Participants earn shares proportional to their contributions, establishing a foundation for secure and transparent decentralized finance (DeFi) activities within the DeFi-Empire ecosystem. This setup enables efficient financial transactions on the blockchain.

## Prerequisites

- Linux OS
- Avalanche CLI installed

## Steps

1. **Create Avalanche Subnet**

   ```bash
   avalanche subnet create acer
   ```
This command initiates the creation of an Avalanche subnet named "acer" using the Avalanche CLI.

2. **Deploy Subnet**

    ```bash
    avalanche subnet deploy acer
    ```
Deploy the newly created "acer" subnet on Avalanche using the Avalanche CLI.

3. **Configure Metamask**

- Open Metamask and configure it to connect to the Avalanche network.
- Add the network details including the RPC URL, ChainID, Symbol, and any other required parameters to Metamask.

4. **Deploy ERC20 and Vault Contracts using Remix**

- Open Remix, an online IDE for Ethereum contracts, and configure it to interact with Avalanche.
- Copy the ERC20 token and Vault contract code into Remix.
- Compile and deploy the contracts on the Avalanche network through Remix.
    - Deploy the ERC20 token contract first, specifying parameters like token name, symbol, and initial supply.
    - Deploy the Vault contract, ensuring it correctly implements the IERC20 interface to interact with KY.

5. **Interact with Contracts**

- After deployment, verify the functionality of the deployed contracts:
    - Test token transfers with the ERC20 token to ensure proper balance management and event logging.
    - Test deposit and withdrawal functionalities with the Vault contract to validate that users can securely manage funds and earn shares proportional to their contributions.

## Authors

- Meet Patil
- Github: [https://github.com/adiepale](https://github.com/adiepale)
