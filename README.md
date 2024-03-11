ERC-721 NFT Project.

This project is an implementation of the ERC-721 standard for non-fungible tokens (NFTs) on the Ethereum blockchain. It was created in response to the hackathon held by Ethereum Nigeria at the University of Lagos campus. The project allows for the creation, ownership, and transfer of unique digital assets.
Overview

The ERC-721 standard defines a set of rules for creating NFTs, which are unique and indivisible digital assets. Each token within the contract is distinct and cannot be replicated or replaced.
Features

    Creation of Unique Tokens: Users can mint new tokens, each with its own distinct properties and metadata.
    Ownership Transfer: Tokens can be transferred between Ethereum addresses, allowing for ownership changes.
    Metadata Storage: Token metadata, such as name, description, and image URI, is stored on-chain or off-chain as per the project's design.

Getting Started

To interact with this ERC-721 contract, you will need an Ethereum or metamask wallet and a compatible Web3 provider. You can deploy this contract on the Ethereum mainnet or any test network.
Prerequisites

    Node.js
    Truffle (for testing and deployment)
    Web3.js (for interacting with the Ethereum blockchain)

Installation

    Clone this repository:

    bash

git clone https://github.com/mrsheun/Eth_Lagos-Hackerton.git

Install dependencies:

bash

    npm install

    Don't forget to configure your metamask wallet and Web3 provider settings in truffle-config.js.

Usage

    Compile the smart contracts:

    bash

truffle compile

Migrate the contracts to the desired Ethereum network:

bash

    truffle migrate --network <network-name>



Contributing

Contributions are welcome! If you'd like to contribute to this project, please follow these steps:

    Fork the repository
    Create a new branch (git checkout -b feature)
    Make your changes
    Commit your changes (git commit -am 'Add feature')
    Push to the branch (git push origin feature)
    Create a new Pull Request

License

This project is licensed under the MIT License.
Acknowledgements

    Ethereum Nigeria and my mentor (Enoch Mbaebie) for organizing the hackathon at the University of Lagos campus.
    OpenZeppelin for their ERC-721 implementation and security audits.
    Truffle Suite for providing development tools and resources for Ethereum smart contracts.
