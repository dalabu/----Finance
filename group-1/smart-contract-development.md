---
description: How to create smart contract on Avalanche chain that can be run by AVM tools,
---

# Smart contract Development



Creating smart contracts on the Avalanche (AVAX) chain involves several steps, including writing the contract code, compiling it, and deploying it to the network. Here's a step-by-step guide on how to do it:

Step 1: Choose a Development Environment

There are two primary options for developing smart contracts on Avalanche:

1. Remix IDE: Remix is a web-based IDE specifically designed for developing Ethereum-based smart contracts. It offers a user-friendly interface and integrates with various tools and libraries.

Image of Remix IDE for smart contract development

2. Hardhat: Hardhat is a popular development framework for Solidity, the primary language for Ethereum smart contracts. It provides a command-line interface (CLI) for managing the development process and interacting with the blockchain.

Image of Hardhat CLI for smart contract deployment

Step 2: Write the Smart Contract Code

Use Solidity to write the code for your smart contract. Solidity is a high-level programming language specifically designed for developing smart contracts. You can either start from scratch or use existing open-source contracts as a reference.

Step 3: Compile the Smart Contract

Once you've written the smart contract code, you need to compile it into bytecode, which is the language the Avalanche Virtual Machine (AVM) understands. This can be done using a compiler like Solc, which is part of the Solidity toolkit.

Step 4: Deploy the Smart Contract

To deploy the smart contract to the Avalanche network, you need to create a transaction that includes the compiled bytecode and the necessary information for deploying the contract. This can be done using a development environment like Remix or the Avalanche CLI.

Step 5: Fund Your C-Chain Address

To interact with your deployed smart contract, you'll need to have funds in your Avalanche wallet. You can fund your C-Chain address using a cryptocurrency exchange or a decentralized exchange (DEX) like Trader Joe or Pangolin.

Here's a simplified overview of the deployment process using Remix IDE:

1. Create a new Remix project
2. Import your Solidity smart contract file (.sol)
3. Select Avalanche C-Chain as the network
4. Compile the smart contract
5. Deploy the smart contract
6. Review and sign the transaction
7. Submit the transaction to the Avalanche network

Once the deployment is successful, your smart contract will be live on the Avalanche network, and you can interact with it using your C-Chain address and the Avalanche wallet of your choice.

\


