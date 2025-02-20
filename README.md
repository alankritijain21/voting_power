# Peer Tipping

## Description
A Solidity-based smart contract that allows users to tip peers as rewards. Users can send ETH to others as tips, and the contract keeps track of the total tips received by each user.

## Smart Contract Address
```
0x52340605DC0b93EBBAc5C4759beBAb3bA22D54F7
```

## Features
- Send ETH tips to peers
- Keeps track of total tips received
- Prevents self-tipping and invalid transactions
- **Community Tipping System** - Allows users to tip others using tokens.
    - **Prompt**: "Implement a tipping mechanism for peer rewards."

## How to Use
1. Deploy the contract on an Ethereum-compatible blockchain.
2. Call the `tip` function with the recipient's address and an ETH amount.
3. Use `getTipsReceived` to check the total tips received by an address.

## License
MIT License

